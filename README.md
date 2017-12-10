# irdp [![GoDoc](https://godoc.org/github.com/armen/irdp?status.png)](https://godoc.org/github.com/armen/irdp) [![Build Status](https://travis-ci.org/armen/irdp.svg?branch=master)](https://travis-ci.org/armen/irdp)

<img width="165" src="http://www.distributedprogramming.net/images/cover-5.png" align="right">

An implementation of [*Introduction to Reliable and Secure Distributed Programming*][irdp] algorithms.

## List of Algorithms

### Chapter 1: Introduction
- Module 1.1 Interface and properties of a job handler ([interface](https://raw.githubusercontent.com/armen/irdp/master/job/handler.go))
	- Algorithm 1.1 Synchronous Job Handler ([code](https://raw.githubusercontent.com/armen/irdp/master/job/sync/sync.go), [algorithm](https://raw.githubusercontent.com/armen/irdp/master/job/sync/sync.txt))
	- Algorithm 1.2 Asynchronous Job Handler ([code](https://raw.githubusercontent.com/armen/irdp/master/job/async/async.go), [algorithm](https://raw.githubusercontent.com/armen/irdp/master/job/async/async.txt))
- Module 1.2 Interface and properties of a job transformation and processing abstraction ([interface](https://raw.githubusercontent.com/armen/irdp/master/job/transformation_handler.go))
	- Algorithm 1.3 Job-Transformation by Buffering ([code](https://raw.githubusercontent.com/armen/irdp/master/job/transformation/transformation.go))

[irdp]: http://distributedprogramming.net
