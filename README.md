**Cyprus Inrtnational University**

**Master Thesis: Detecting Ddos Attacks Using Machine Learning Methods**

Student: Farog Basher.
stdNumber: 21903332
Advisor: Dr.Devrim SERAL.

GoogleDriveLinkForFiles: https://drive.google.com/drive/folders/1O4kEtF767U_Sp9yguTYxmf4j13Hj85-6?usp=drive_link

----------------------------------------------------------------------------------------------------------------------------------

# DdosAttackClassifier
Machine Learning Classifer For Ddos attacks According to given DataSets.

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 
MainDataSetsToTrainedMyModelOn: (CIC-DDoS2019)

https://www.unb.ca/cic/datasets/ddos-2019.html

----------------------------------------------------------------------------------------------------------------------------------

__Code Explenations:__
__1stPart:__
Train the Models on given data set with special Parameters used for Detecting Ddos Traffic

__2ndPart:__
Load the trained weight i got for the training models into the Notebook Storage.

__3rdPart__
Load any diffrent Csv file and test the same methology on it and see the results.

----------------------------------------------------------------------------------------------------------------------------------
__Machine Learning Models Used:__
__Random Forest:__
Why use it? Random Forest is like a group decision-making process where each decision (tree) contributes to the final verdict (prediction).
What's good about it? It's good at handling a lot of information and finding patterns, even if they're not straightforward.
Why might it be useful for DDoS detection? DDoS attacks can have complex patterns, and Random Forest is good at spotting those patterns even if they're not simple.

__Logistic Regression:__
Why use it? It's like looking at historical data to make predictions based on similarities.
What's good about it? It's easy to understand and works well when there are only two outcomes (like "attack" or "no attack").
Why might it be useful for DDoS detection? It's good at quickly figuring out if something looks like a DDoS attack or not based on past patterns.

__Support Vector Machine (SVM):__
Why use it? It's like drawing lines to separate different types of data.
What's good about it? It's good at finding the best lines to separate different types of data, even if they're mixed up.
Why might it be useful for DDoS detection? DDoS attacks can be tricky to spot because they often look like normal traffic. SVM can help draw clear lines between normal and suspicious traffic.

----------------------------------------------------------------------------------------------------------------------------------
__Addidtionally__
-Aws used In this project to get Jupiter Notebooks.
-Aws S3Buckets used in this project to store DataSets for better and faster Loading Since it internal Network.
-HardwareUsed: Virtual Machine From Amazon Web Services(AWS) 8vCPU & 32GBram
-CicFlowMerter: a network traffic flow generator distributed by CIC to generate network traffic features from given Pcap files, used in this project to generate a Csv files compatible with my model so ML model can test verity of data according to its testing data.

----------------------------------------------------------------------------------------------------------------------------------
Datasets:
Train DataSet:


Testing DataSet"


----------------------------------------------------------------------------------------------------------------------------------

__Challenges:__
-which data should i count on to idinitfy the traffic is ligit of not
-try to modify the code to rely on Pcap files instead of Csv files becuase it cant have the same headers and labeled between available datasets. and it can improve later by implmentanig RealTime Detection
    proposed featuars to Detect non ligitmet traffic from the train data set:
    Packet Count: Total number of packets in the network flow.
    Packet Size Distribution: Distribution of packet sizes within the flow (e.g., mean, standard deviation, skewness, kurtosis).
    Interarrival Time: Time between consecutive packets in the flow.
    Protocol Distribution: Distribution of protocols used in the flow (e.g., TCP, UDP, ICMP).
    Source/Destination IP Address: Unique count or entropy of source and destination IP addresses.
    Source/Destination Port: Unique count or entropy of source and destination port numbers.
    Traffic Volume: Total amount of data transferred in the flow.
    Traffic Rate: Average or maximum data transfer rate within the flow.
    Packet Length Distribution: Distribution of packet lengths within the flow.
    Fragmentation Rate: Ratio of fragmented packets to total packets.
    SYN/ACK Ratio: Ratio of SYN packets to ACK packets in TCP traffic.
    DNS Query Rate: Rate of DNS queries within the flow.
    ICMP Echo Request/Reply Ratio: Ratio of ICMP echo request to reply packets.
    HTTP Request Rate: Rate of HTTP requests within the flow.
    SSL Handshake Rate: Rate of SSL handshake packets within the flow.

