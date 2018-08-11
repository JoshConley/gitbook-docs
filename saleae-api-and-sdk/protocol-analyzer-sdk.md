# Custom Protocol Analyzers

### Protocol Analyzer SDK for Custom Protocol Analyzers

The Saleae Analyzer SDK lets you make your own custom protocol analyzers. The framework is very flexible. You can do everything we can do \(we use the same SDK\). You'll be creating a shared library \(.dll, .so, or .dylib\) that will be loaded by the Logic software as a plugin.

While there are many advantages to providing the SDK in this format, implementation of a custom protocol will probably take an experienced C++ developer at least a full day, and possibly up to a week, to complete. You will probably want to have had considerable programming experience, probably significant C++ experience, before taking it on.

That said, you can get away with implementing only a small part of the full capability of the analyzer. For example, you could have only one setting \(the input channel\(s\) to use\), and you could skip creating simulated data to test against, not bothering to provide for data export or tabular display.

Further, by default, you will start out with a fully featured and maximally simple analyzer—SimpleSerialAnalyzer. The documentation will walk you through how to modify it to suit your needs, as well as what parts can be left empty.

Let us know what you think.

**Latest SDK Release Works with All Software from 1.1.32 and Newer**

* [Sample Analyzer, Analyzer SDK, and Documentation on Github](https://github.com/saleae/SampleAnalyzer)
* [Source Code to all Saleae Analyzers, from release 1.2.17](http://downloads.saleae.com/SDK/SaleaeAnalyzerSource-1.2.17.zip) \(the source code for all our analyzers\) These don't change frequently, but updated copies are available on request.
* [Older zip file release. For reference only.](http://downloads.saleae.com/betas/1.1.32/SaleaeAnalyzerSdk-1.1.32.zip)

**Documentation and Getting Started**

To get started, please first read the readme file for the SampleAnalyzer repository:

* [Readme](https://github.com/saleae/SampleAnalyzer/blob/master/readme.md)

And then read the Setup documentation:

* [Analyzer SDK Setup](https://github.com/saleae/SampleAnalyzer/blob/master/docs/Analyzer%20SDK%20Setup.md)

The documentation for the Analyzer SDK can be found in the pdf and on GitHub. This document still needs to be updated and migrated to markdown, but the documentation for the C++ SDK is largely up-to-date, although it is missing details on the Protocol Search system. Please do not use the first section of this for the setup instructions since they are outdated.

* \[Saleae Analyzer SDK Documentation\]\([https://github.com/saleae/SampleAnalyzer/blob/master/docs/Saleae Analyzer SDK \(older\).pdf](https://github.com/saleae/SampleAnalyzer/blob/master/docs/Saleae%20Analyzer%20SDK%20%28older%29.pdf)\)

**Older 1.1.14 Release**

* [Saleae Analyzer SDK 1.1.14](http://downloads.saleae.com/SDK/SaleaeAnalyzerSdk-1.1.14.zip) \(includes User's Guide\)
* [Saleae Analyzer Source Code 1.1.14](http://downloads.saleae.com/SDK/Saleae%20Analyzer%20Source%201.1.14.zip) \(the source code for all our analyzers\)
