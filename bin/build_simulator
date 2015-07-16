#!/bin/bash

set -e

SCRIPT_HOME="$( cd "$( dirname "$0" )" && pwd )"
cd $SCRIPT_HOME/..

mkdir -p tmp

tar zcvf tmp/cpufixed.tar.gz -C services/cpufixed/build .
tar zcvf tmp/cpuranmdom.tar.gz -C services/cpurandom/build .
tar zcvf tmp/lookbusy.tar.gz -C services/lookbusy/build .
tar zcvf tmp/stress.tar.gz -C services/stress/build .


cd - > /dev/null
