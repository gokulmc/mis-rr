# Experimental Evaluation of Multi-Installment Scheduling Strategy for SAR Image Reconstruction

---
### Abstract 
Radar loads, especially Synthetic Aperture Radar(SAR) image reconstruction loads use a large volume of data collected from satellites to create a high-resolution image of the earth. To design near-real-time applications that utilise SAR data, speeding up the image reconstruction algorithm is imperative. This can be achieved by deploying a set of distributed computing infrastructures connected through a network. Scheduling such complex and large divisible loads on a distributed platform can be designed using the Divisible Load Theory(DLT) framework. We performed distributed SAR image reconstruction experiments using the SLURM library on a cloud virtual machine network using two scheduling strategies, namely the Multi-Installment Scheduling with Result Retrieval(MIS-RR) strategy and the traditional EQual-partitioning Strategy(EQS). The DLT model proposed in the MIS-RR strategy is incorporated to make the load divisible. Based on the experimental results and performance analysis carried out using different pixel lengths, pulse set sizes, and the number of virtual machines, we observe that the time performance of MIS-RR is much superior to that of EQS. Hence the MIS-RR strategy is of practical significance in reducing the overall processing time, and cost, and in improving the utilisation of the compute infrastructure. Furthermore, we note that the DLT-based theoretical analysis of MIS-RR coincides well with the experimental data, demonstrating the relevance of DLT in the real world.

### Keywords
`Synthetic Aperture Radar` `distributed computing` `heterogeneous cluster` `Divisible Load Theory` `SLURM` `Multi-Installment Scheduling`

## Overview 📊
The project evaluates a **multi-installment scheduling strategy** for SAR image reconstruction, aiming to improve time performance, cost efficiency, and infrastructure utilization.

## Manuscript Information 📝
- **Title**: Distributed SAR Image Reconstruction using a Network of Virtual Machines using Divisible Load Paradigm
- **Authors**: Gokul MC, Bharadwaj Veeravalli, Koen Mouthaan, John Lee Wen-Hao
- **Journal**: Journal of Parallel and Distributed Computing
- **Manuscript Number**: JPDC-D-23-00308
- **Article Type**: Research Paper
- **Section/Category**: Applications

## Experiment Details 🔬
- **SLURM**: Used for cloud virtual machine network experiments
- **Strategies**: Comparison between MIS-RR and EQS
- **DLT Model**: Incorporated in MIS-RR strategy
- **Performance Metrics**: Pixel lengths, pulse set sizes, VM count

## Findings 💡
- **MIS-RR vs. EQS**: MIS-RR showed better time performance
- **Theoretical vs. Experimental**: DLT-based analysis matched with results
- **Significance**: Reduction in processing time and improved infrastructure use
