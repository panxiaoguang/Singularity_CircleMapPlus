# Singularity_CircleMapPlus

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/panxiaoguang/Singularity_CircleMapPlus/build.yml?style=flat-square)](https://github.com/panxiaoguang/Singularity_CircleMapPlus/actions/workflows/build.yml)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/panxiaoguang/Singularity_CircleMapPlus?style=flat-square)

Using github action to build a singularity image for Circle-Map-cpp automaticlly

# Introduction

Circle-Map is a great tool to detect thousands of extrachromosomal circular DNA (eccDNA). Thanks to this tool, we can easily get eccDNA from Circle-Seq data! Recently, with the collaboration of several persons from BGI-Qingdao, Circle-Map-Cpp has been built and available on [BGI-Qingdao/Circle-Map-cpp](https://github.com/BGI-Qingdao/Circle-Map-cpp), But it uses some extra tools and must be compiled to a binary, which make a fence for using.

SingularityCE is a container platform. It allows you to create and run containers that package up pieces of software in a way that is portable and reproducible. You can build a container using SingularityCE on your laptop, and then run it on many of the largest HPC clusters in the world, local university or company clusters, a single server, in the cloud, or on a workstation down the hall. Your container is a single file, and you don’t have to worry about how to install all the software you need on each different operating system.

So I use Github Action to help me to build a SingularityCE image with bedtools, python3 and other packages for easily using.

# Usage

For usage, please go to the Circle-Map-Cpp official repository !
