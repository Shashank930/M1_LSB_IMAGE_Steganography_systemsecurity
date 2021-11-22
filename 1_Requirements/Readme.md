# M1_image_steganography_security
## Requirements
1.The application accept an image file say .bmp along with the a text file which contains the message to be steged
2.Analize the size of the message file and the data part of the .bmp file to check whether the messsage could fit in the provided .bmp image
3.Provide a option to steg a magic string which could be usefull to identify whether the image is steged or not
4.The appliaction should provide a option to decrpt the file
5.This has to be an command line apliaction and all the options has to be passed as an command line argument


## Introduction
Cryptography is the arts and science of keeping message secure from the unauthorized disclosure i.e., it converts the message into scrambled message so that the message won’t be in the meaningful format. Broadly, cryptosystem is classified into two types namely 
 (a) symmetric or private key cryptosystem 
 (b) asymmetric or public key cryptosystem. Sender and receiver share a single key that is common for both the participants in symmetric key cryptosystem. i.e., Sender converts the message into scrambled message using the shared key and then the converted 
scrambled message is transferred through secure channel to the other end. After the message is received by the receiver, the message gets decrypted using the same shared secret key. This cryptosystem is mainly used for achieving confidentiality. In asymmetric key cryptosystem, two dissimilar keys called public key and private key is used. To achieve confidentiality, the message is encrypted with the help of receiver’s public key to obtain cipher text and then the received cipher text gets decrypted at the other end by the corresponding private key holder. To achieve authentication, the plaintext is encrypted using sender’s secret key and then the converted one is communicated to the other end.
The received data is then converted into original message using shared public key. To achieve confidentiality and authentication service, sender encrypts the message using their secret key and then the converted message is given as input for the second stage of encryption to get the final cipher text using receiver’s public key. Then, this final output is injected into the network to send it to the recipient. Whenever the messsage is received by the recipient, he uses his private key to unscramble the message and then it is decrypted once again using public key of sender to get the original plaintext. This scheme is used for achieving both confidentiality and authentication services.
## Research
![RESEARCH](https://user-images.githubusercontent.com/94338510/142851520-7d4a2731-bd75-41f5-b066-461751f3f59f.PNG)
A new technique for  data hiding  has been proposed and implemented , based on edge detection and modifed RSA algorithm. In the modifed RSA algorithm, two pairs of keys are generated. In this, frst the message is encrypted with the help of revised RSA algorithm to convert the message into secret message.



## Cost and Features and Timeline
1. (2016) 
suggested a technique called Knight Move’s algorithm to generate several number of squares, to embed the secret data. It achieves high payload and took less computational time.
2. (2018)
suggested a inherent scheme to select the perfect regions of the cover medium to embed the confdential data using LSB technique based on a random key.
3. NEW GENERATION SECURITY TECHNIQUE
The message is encrypted with the aid of modified/revised RSA algorithm. Moreover, two diferent public keys and private keys are used. Only if those two diferent private keys are compromised, the secret message will be exposed

## Defining Our System
    A new technique for  data hiding  has been proposed and implemented , based on edge detection and modifed RSA algorithm. In the modifed RSA algorithm, two pairs of keys are generated. In this, first the message is encrypted with the help of revised RSA algorithm and then decrypted by authorised user 
## SWOT ANALYSIS
a) Strengths
Improved efciency, security and imperceptibility properties of information hiding from the
results.

b) Weaknesses
Weaknesses, like strengths, are inherent features of your projects, so focus on your people, resources, systems, and procedures.

c) Opportunity
They usually arise from situations outside your organization, and require an eye to what might happen in the future.

d) Threats
Threats include anything that can negatively affect your business from the outside, such as supply-chain problems, shifts in market requirements, or a shortage of recruits.

# 4W&#39;s and 1&#39;H

## Who:

User and CLient

## What:

A new technique for  data hiding  has been proposed and implemented , based on edge detection and modifed RSA algorithm 

## When:

New generation technique effective in 2021

## Where:

 useful for user and client for encrypted communicaion 

## How:

Using edge detection and RSA algorithm with C programming 

# Detail requirements
## High Level Requirements:
![HLR1](https://user-images.githubusercontent.com/94338510/142860273-05a23b06-b0c8-4be6-bc5e-34fe49ecca3c.PNG)



##  Low level Requirements:
![LLR2](https://user-images.githubusercontent.com/94338510/142861194-7a190ee5-5425-4c1a-bc7d-0ca5b72b5871.PNG)






