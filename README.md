homebrew-spikesorting
=====================

homebrew tap that contains formulas for software used in spike sorting.

Just run the following to add these formulas to your homebrew installation:

    brew tap FlorianFranzen/spikesorting

NeuroScope, Klusters, NDManager, the NDManager plugins and libneurosuite (formerly
libklustersshared) have moved to the Neurosuite tap, which builds the current Qt 6 versions:

    brew tap neurosuite/neurosuite
    brew install neuroscope klusters ndmanager ndmanager-plugins

Existing installations are migrated to the new tap by `brew update`.
