# Morse-Code-Encoder-and-Decoder-Project-Lab-view
Morse Code Encoder and Decoder using LabVIEW that converts text to Morse signals and decodes Morse back into text using timing-based logic and dataflow programming.
# 📡 Morse Code Encoder & Decoder (LabVIEW)

##  Overview

This project implements a **Morse Code Encoder and Decoder** using LabVIEW.
The system converts text into Morse code (dots and dashes) and also decodes Morse signals back into readable text using timing-based logic.

The project demonstrates **dataflow programming, string processing, and real-time signal interpretation** in a software-only environment.

---

##  Problem Statement

Traditional communication systems require complex hardware and are not suitable for simple or emergency communication.

This project aims to:

* Convert text into Morse code signals
* Decode Morse signals back into text
* Work without external hardware
* Provide a simple and cost-effective solution

---

##  Proposed Solution

The system is divided into two main modules:

### Encoder (Text → Morse)

* Takes input text
* Converts characters using a lookup table
* Displays Morse code using dots (.) and dashes (-)

###  Decoder (Morse → Text)

* Takes Morse input
* Uses timing/logic to interpret signals
* Converts Morse into readable text

---

##  Features

* Real-time encoding and decoding
* Event-driven execution (LabVIEW Event Structure)
* Accurate Morse mapping using lookup logic
* Software-only implementation (no hardware required)

---

##  Working Principle

* Each character is mapped to Morse code using predefined rules
* Encoding uses **string processing + loop + case structure**
* Decoding uses **pattern matching + timing logic**
* Output is built using **shift registers**


##  Results

* Text successfully converted to Morse code
* Morse signals accurately decoded into text
* Real-time performance achieved

---

##  Discussion

* System works efficiently in software environment
* Accuracy depends on correct timing input
* LabVIEW simplifies implementation using graphical programming

---

##  Conclusion

The project successfully demonstrates a **simple and effective digital communication system** using Morse code.

It highlights:

* Dataflow programming
* Signal timing logic
* Software-based communication systems

This project can be extended for **assistive communication and hardware integration**.


##  References

* Sae-tang & Mittrapiyanuruk (2013)
* Tran et al. (2014)
* NI LabVIEW Documentation
* ITU Morse Code Standards

---

##  Future Improvements

* Real-time hardware integration (Arduino / sensors)
* Audio-based Morse decoding
* Mobile or GUI-based interface

---
