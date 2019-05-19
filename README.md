# Line Width Normalization

## Overview

This code provides a pre-trained model of a part (line width normalization) of the research paper:

```
   Real-Time Data-Driven Interactive Rough Sketch Inking
   Edgar Simo-Serra, Satoshi Iizuka, Hiroshi Ishikawa
   ACM Transactions on Graphics (SIGGRAPH), 2018
```

See our [project page](https://esslab.jp/~ess/research/inking/) for more detailed information.

## Dependencies

- [PyTorch](http://pytorch.org/)
  [torchvision](http://pytorch.org/docs/master/torchvision/)
- [pillow](http://pillow.readthedocs.io/en/latest/index.html)

All packages should be part of a standard PyTorch install. For information on how to install PyTorch please refer to the [torch website](http://pytorch.org/).

## Usage

```
python thin.py [infile] [outfile]
```

By default `infile` is set to "in.png" and `outfile` is set to "out.png".

## Citing

If you use these models please cite:

```
@Article{SimoSerraSIGGRAPH2018,
   author    = {Edgar Simo-Serra and Satoshi Iizuka and Hiroshi Ishikawa},
   title     = {{Real-Time Data-Driven Interactive Rough Sketch Inking}},
   journal   = "ACM Transactions on Graphics (SIGGRAPH)",
   year      = 2018,
   volume    = 37,
   number    = 4,
}
```

## Acknowledgements

This work was partially supported by JST CREST Grant Number JPMJCR14D1, and JST ACT-I Grant Numbers JPMJPR16UD and JPMJPR16U3.

## License

The model weights are shared under the Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license. See [LICENSE](./LICENSE) for more information
