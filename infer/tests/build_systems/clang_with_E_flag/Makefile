# Copyright (c) 2017-present, Facebook, Inc.
#
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.

TESTS_DIR = ../..

CLANG_OPTIONS = -E -c
INFER_OPTIONS = --report-custom-error --developer-mode --project-root ../codetoanalyze
INFERPRINT_OPTIONS = --issues-tests

SOURCES = ../codetoanalyze/hello.c

include $(TESTS_DIR)/clang.make
