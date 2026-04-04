# Networking

### What is the Internet?

The Internet is a global set of interconnected networks that cooperate with each other, sending and receiving information through common patterns.

Everything we access online is located somewhere on the global Internet. All destinations are connected to a local network that receives and sends information over the internet.

### Local Networks

There are several network sizes. They can vary from a simple network with only two computers to networks connecting millions of devices.

Networks used in small offices, homes, or home offices are known as **SOHO** (Small Offices Home Offices) networks.

### Data Transmission

Data is a **collection of facts, numbers, words, observations, or other useful information**.

Computers and networks only work with **binary digits** (zeros and ones). All data is stored and transmitted as a set of bits. Each bit can have only two possible values: 0 or 1.

The term *bit* is the short for "binary digit" and represents the smallest unit of data. Computers read data based on bits patterns.

A bit is stored and transmitted as one in two distinct possible states. For instance, a light switch can be turned on or off; in binary terms, these states correspond to 1 and 0, respectively.

An input device (keyboard, mouse, microphone) converts the human inputo into binary code so that the CPU can process and store it.

An output device (printer, speakers, monitor) does the opposite: it converts binary data into a form that can be recognized by humans.

The code that most computers use to understand binary data is **ASCII** (American Standard Code for Information Interchange). In this system, each character is represented by eight bits.

For example:

 - A = 01000001
 - 9 = 00111001
 - \# = 00100011

You can find the full ASCII table at the [link](https://www.ime.usp.br/~kellyrb/mac2166_2015/tabela_ascii.html)

After data is encoded into a set of bits, it must be converted into signals that can be transmitted over network media to their destination.

Network media refers to the physical medium through which signals are transmitted. Examples: copper wire, fiber optic cable, and electromagnetic waves transmitted through the air.

A signal is an optical or electrical pattern that is transmitted from one connected device to another.

Signals can often be converted before they reach their destination, as the transmission medium may change between the source and the destination.

These are common methods of signal transmission:
 - Electrical signals: electrical pulses
 - Optical signals: light pulses
 - Wireless signals: infrared, microwaves, and radio waves.

### Bandwidth

Different physical media support bits transmission at different speeds. Data transmission is commonly measured in terms of bandwidth and transmission rate.

Bandwidth é the ability of a physical medium to transmit data. Digital bandwidth measures the amount of data that can be transmitted from one place to another over a given period of time. It's usually measured by the number of bits that can (theorically) be transmitted over the network medium in one second.

 - Thousands of bits per second (kbps)
 - Millions of bits per second (Mbps)
 - Billions of bits pe second (Gbps)

### Transmission Rate

Like bandwidth, transmission rate is a measure of how many bits are transmitted through a physical mediu during a given period of time.

There are many factors that influnce in transmission rate:
 - The amount of data transmitted and received over a connection
 - The types of data being transmitted
 - Latency caused by the number of network devices between the source and destination

Latency refers to the time it takes for data to travel from one point to another.

Transmission rate measurements do not consider the validaty or usefullness of the transmitted and received bits.

In a internetwork or in a network with multiple segments, the transmission rate cannot exceed the speed of the slowest link along the path between the source and destination devices. Even if all segments (or most of them) have high bandwidth, it only takes one segment with lower bandwidth to slow down the overall network performance.

