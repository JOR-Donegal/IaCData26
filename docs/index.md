# Introduction

!!! abstract "Infrastructure as Code - Data"

To fully automate configurations, we need a backend database which is vendor and equipment agnostic, but rich and flexible enough to capture all the requirements.

_Serialization_ is the process of converting an object or data structure into a format that can be stored or transmitted and later reconstructed.

It allows you to:

- Save data to a file
- Send data over a network
- Share data between different applications
- Cache data for faster retrieval
- Store configuration in a portable format

XML, JSON and YAML are ways of serializing, storing data and communicating it. 

The data file itself does not do anything and you cannot run it like a programme. If you are using these data files, you need a programme to generate the files and a programme to consume its content.
