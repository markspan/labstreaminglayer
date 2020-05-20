Supported Devices and Tools
###########################

**For device applications and tools hosted on GitHub, please make sure to read the respective repository's README and to check the release page for downloads.**

The lab streaming layer was originally developed to facilitate human-subject experiments that involve multi-modal data acquisition, including both brain dynamics (primarily EEG), physiology (EOG, EMG, heart rate, respiration, skin conductance, etc.), as well as behavioral data (motion capture, eye tracking, touch interaction, facial expressions, etc.) and finally environmental and program state (for example, event markers).

Supported EEG Hardware
**********************
The majority of EEG systems on the market are currently compatible with LSL.


The following systems are supported by programs included in the LSL distribution (untested systems marked with a (u)):
  * `ABM B-Alert X4/X10/X24 wireless <https://github.com/labstreaminglayer/App-BAlert>`__ (u)
  * `BioSemi Active II Mk1 and Mk2 <https://github.com/labstreaminglayer/App-BioSemi>`__
  * `Blackrock Cerebus/NSP <https://github.com/labstreaminglayer/App-BlackrockTimestamps>`__ (timestamps only)
  * `Brain Products BrainAmp series <https://github.com/labstreaminglayer/App-BrainProducts>`__
  * `Cognionics dry/wireless <https://github.com/labstreaminglayer/App-Cognionics>`__
  * `EGI AmpServer <https://github.com/labstreaminglayer/App-EGIAmpServer>`__
  * `Enobio dry/wireless <https://github.com/labstreaminglayer/App-Enobio>`__ (u) (please see vendor-provided above)
  * `g.Tec g.USBamp <https://github.com/labstreaminglayer/App-g.Tec/tree/master/g.USBamp>`__ (buggy at high sampling rates)
  * `g.Tec g.NEEDaccess <https://github.com/labstreaminglayer/App-g.Tec/tree/master/g.NEEDaccess>`__ (including g.USBamp, g.HIamp, g.Nautilus)
  * `MINDO dry/wireless <https://github.com/labstreaminglayer/App-MINDO>`__
  * `Neuroscan Synamp II and Synamp Wireless <https://github.com/labstreaminglayer/App-Neuroscan>`__ (u)


The following devices support LSL via vendor-provided software:
  * `ANT eego sports <https://www.ant-neuro.com/products/eego_sports>`__
  * `Brain Products actiCHamp/actiCHamp Plus <https://github.com/brain-products/LSL-actiCHamp>`__
  * `Brain Products LiveAmp <https://github.com/brain-products/LSL-LiveAmp/>`__
  * `BrainVision RDA client <https://github.com/brain-products/LSL-BrainVisionRDA>`__
  * `Cognionics (all headsets) <http://www.cognionics.com/>`__
  * `EB Neuro BE Plus LTM <http://www.ebneuro.biz/en/neurology/ebneuro/galileo-suite/be-plus-ltm>`__
  * `InteraXon Muse <http://www.choosemuse.com/>`__
      * :doc:`MU-01 - Muse - Released 2014 Example with Matlab <matlab_example_with_muse>`
      * `MU-02 - Muse - Released 2016 <https://github.com/alexandrebarachant/muse-lsl>`__
      * `MU-03 - Muse 2 - Released 2018 <https://github.com/alexandrebarachant/muse-lsl>`__
  * `mBrainTrain SMARTING <http://www.mbraintrain.com/smarting/>`__
  * neuroelectrics `(Enobio <http://www.neuroelectrics.com/products/enobio/>`__, `StarStim <https://www.neuroelectrics.com/solutions/starstim>`__) via `NIC2 <https://www.neuroelectrics.com/solution/software-integrations/nic2>`__.
  * `OpenBCI (all headsets) <http://docs.openbci.com/software/06-labstreaminglayer>`__


The following devices support LSL natively without any additional software:
  * `Foc.us EEG Dev Kit <https://foc.us/eeg>`__
  * `NeuroBehavioralSystems LabStreamer <https://www.neurobs.com/menu_presentation/menu_hardware/labstreamer>`__


The following systems are also supported by a separate program, the :doc:`OpenViBE acquisition server <ovas>` (unstable systems marked with a (u)):
  * ANT Neuro ASALAB EEG
  * Brain Products QuickAmp, V-Amp, and BrainAmp series
  * CTF/VSM (u)
  * EGI NetAmp (u)
  * g.USBamp
  * Emotiv EPOC
  * Micromed SD LTM
  * MindMedia NeXus32
  * Mitsar EEG 202 (u)
  * OpenEEG ModularEEG and MonolithEEG
  * TMSi Porti32 and Refa32


Supported Eye Tracking Hardware
*******************************
Several eye tracking systems are currently supported by LSL and included in the distribution (untested systems marked with a (u)):
  * Eye Tribe Tracker Pro
  * :lslrepo:`SMI iViewX <SMIEyetracker>`
  * :lslrepo:`SMI Eye Tracking Glasses <SMIEyetracker>`
  * SR Research Eyelink (very basic)
  * Tobii Eye trackers
      * :lslrepo:`Tobii Pro <TobiiPro>`
      * :lslrepo:`Tobii StreamEngine (consumer devices) <TobiiStreamEngine>`
      * :lslrepo:`Tobii other (older app) <Tobii>` (u)
  * Custom 2-camera eye trackers (with some hacking)
  * :lslrepo:`Pupil-Labs <PupilLabs>`

Supported Human Interface Hardware
**********************************
A wide range of Windows-compatible input hardware is supported by LSL and included with the distribution:
  * :lslrepo:`Input devices (keyboards, trackballs, presenters, etc.) <Input>`
  * :lslrepo:`DirectX-compatible joysticks, wheels, gamepads and other controllers <GameController>`
  * :lslrepo:`Nintendo Wiimote and official expansions <Wiimote>`

Supported Motion Capture Hardware
*********************************
Several motion-capture systems are currently supported by LSL and included in the distribution. These are:
  * :lslrepo:`AMTI force plates with serial I/O <AMTIForcePlate>`
  * :lslrepo:`PhaseSpace`
  * :lslrepo:`Microsoft Kinect <KinectMocap>`
  * :lslrepo:`NaturalPoint OptiTrack <OptiTrack>` (some versions)
  * :lslrepo:`OpenVR`
  * `Qualisys <https://github.com/qualisys/qualisys_lsl_app>`__

Supported Multimedia Hardware
*****************************
Support for standard Windows-compatible multimedia hardware is included:
  * DirectShow-compatible video hardware
  * :lslrepo:`Qt-compatible audio input <AudioCapture>`

Supported Stimulation Hardware
******************************
The following stimulation devices (TMS, TDCS / TACS) have LSL support:
  * `Soterix Medical MXN-33 Transcranial Electrical Stimulator <https://soterixmedical.com/research/hd/mxn-33>`__

Supported Stimulus Presentation Software
****************************************
The following stimulus presentations systems are usable out of the box with LSL:
  * `Neurobehavioral Systems Presentation <https://www.neurobs.com/>`__
  * `iMotions <https://www.imotions.com/>`__
  * Psychopy (using LSL for Python)
  * OpenSesame (using LSL for MATLAB)
  * PsychToolbox (using LSL for MATLAB)
  * Unity (using LSL for C#)
  * `Simulation and Neuroscience Application Platform (SNAP) <https://github.com/sccn/SNAP>`__
  * `Reiz <https://github.com/pyreiz/pyreiz>`__

Miscellaneous Hardware
**********************
The following miscellaneous hardware is supported:
  * :lslrepo:`Generic serial port <SerialPort>`
  * :lslrepo:`Measurement Computing DAQ <MeasurementComputing>`
  * `biosignalsplux sensors using OpenSignals <https://www.biosignalsplux.com/index.php/software/apis>`__
  * :lslrepo:`Vernier Go Direct sensors <vernier>`
  * `Tyromotion Amadeo Robot <https://github.com/pyreiz/ctrl-tyromotion>`__
