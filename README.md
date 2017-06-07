# Mass2PDF

Large scale, multithreaded PDF converter written in c#

## Summary

This is a converter that was designed to be used with thousands of files. Originally designed to convert mass amounts of TIF files to PDF. I am currently in the process of refactoring the code to be a standalone product. Eventually I'd like to support multiple formats as well but for the initial code commits, it will be TIF > PDF. Any contributions would be appreciated.

## Goals

This software will convert as many files as possible, as fast as possible. In testing I was able to convert 20,000, 200-300 page TIF documents to PDF in a very short amount of time. real benchmarks to come.
