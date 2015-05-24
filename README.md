Epoclive
========

[![Join the chat at https://gitter.im/minetics/epoclive](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/minetics/epoclive?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Stream data from Epoc headset and perform BCI analysis.

To use Epoclive

```
$ epoc -h
usage: epoclive [--args]

epoc live data stream

optional arguments:
  -h, --help  show this help message and exit
  --fft       run FFT analysis
  --get-data  read data from sensors
  --hht       run HHT analysis
  --setup     setup epoc live
  --ssvep     steady-state visually evoked potential
  --stft      run STFT analysis
  --wavelet   show wavelet transform
  -a          all sensors
  -c          channel of sensor
  -d          total duration
  -i          path to get input
  -o          path to store output
```

To get real-time data from all sensors.

```
$ epoc --get-data -a
```

![$ epoc --get-data -a](https://cloud.githubusercontent.com/assets/12416402/7783299/cb67b966-013d-11e5-9a9a-8cc68246d951.png)
