
all:

include ../kaldi.mk

TESTFILES =

OBJFILES = online-gmm-decodable.o online-feature-pipeline.o online-ivector-feature.o \
           online-nnet2-feature-pipeline.o online-gmm-decoding.o online-timing.o \
           online-endpoint.o onlinebin-util.o online-speex-wrapper.o \
           online-nnet2-decoding.o online-nnet2-decoding-threaded.o \
           online-nnet3-decoding.o

LIBNAME = kaldi-online2

ADDLIBS = ../gmm/kaldi-gmm.a ../transform/kaldi-transform.a ../feat/kaldi-feat.a \
     ../lat/kaldi-lat.a ../decoder/kaldi-decoder.a ../hmm/kaldi-hmm.a \
     ../nnet2/kaldi-nnet2.a ../nnet3/kaldi-nnet3.a ../chain/kaldi-chain.a \
     ../ivector/kaldi-ivector.a \
     ../cudamatrix/kaldi-cudamatrix.a ../matrix/kaldi-matrix.a \
     ../util/kaldi-util.a ../thread/kaldi-thread.a ../base/kaldi-base.a




include ../makefiles/default_rules.mk

