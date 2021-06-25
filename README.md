# TnP-S4B-scripts
TnP configs scripts for Lepton ISO SFs used in S4B search

## Electron
EGamma TnP at <https://github.com/cms-egamma/egm_tnp_analysis>

### 2017

```
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2017_S4B.py --flag S4BISO --checkBins
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2017_S4B.py --flag S4BISO --createBins
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2017_S4B.py --flag S4BISO --createHists
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2017_S4B.py --flag S4BISO --doFit
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2017_S4B.py --flag S4BISO --doFit --mcSig --altSig
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2017_S4B.py --flag S4BISO --doFit --altSig
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2017_S4B.py --flag S4BISO --doFit --altBkg
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2017_S4B.py --flag S4BISO --sumUp
```

### 2018

```
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2018_S4B.py --flag S4BISO --checkBins
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2018_S4B.py --flag S4BISO --createBins
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2018_S4B.py --flag S4BISO --createHists
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2018_S4B.py --flag S4BISO --doFit
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2018_S4B.py --flag S4BISO --doFit --mcSig --altSig
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2018_S4B.py --flag S4BISO --doFit --altSig
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2018_S4B.py --flag S4BISO --doFit --altBkg
python tnpEGM_fitter.py etc/config/settings_ele_ReReco2018_S4B.py --flag S4BISO --sumUp
```

## Muon
Muon TnP at <https://gitlab.cern.ch/cms-muonPOG/spark_tnp>

### 2017

```
./tnp_fitter.py flatten muon generalTracks Z Run2017 configs/legacy_Z_S4B.json --baseDir ./S4BISO_2017
./tnp_fitter.py fit muon generalTracks Z Run2017 configs/legacy_Z_S4B.json --baseDir ./S4BISO_2017
./tnp_fitter.py prepare muon generalTracks Z Run2017 configs/legacy_Z_S4B.json --baseDir ./S4BISO_2017
```

### 2018

```
./tnp_fitter.py flatten muon generalTracks Z Run2018 configs/legacy_Z_S4B.json --baseDir ./S4BISO_2018
./tnp_fitter.py fit muon generalTracks Z Run2018 configs/legacy_Z_S4B.json --baseDir ./S4BISO_2018
./tnp_fitter.py prepare muon generalTracks Z Run2018 configs/legacy_Z_S4B.json --baseDir ./S4BISO_2018
```
