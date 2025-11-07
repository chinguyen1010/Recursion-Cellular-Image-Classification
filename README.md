# Recursion-Cellular-Image-Classification
CellSignal: Disentangling biological signal from experimental noise in cellular images


Description:
<img width="350" height="350" alt="image" src="https://github.com/user-attachments/assets/f161ff0e-6b90-4fa3-b9f6-4d9dc4f3d10f" />


The cost of some drugs and medical treatments has risen so high in recent years that many patients are having to go without. You can help with a classification project that could make researchers more efficient.

One of the more surprising reasons behind the cost is how long it takes to bring new treatments to market. Despite improvements in technology and science, research and development continues to lag. In fact, finding new treatments takes, on average, more than 10 years and costs hundreds of millions of dollars.

Recursion Pharmaceuticals, creators of the industry’s largest dataset of biological images, generated entirely in-house, believes AI has the potential to dramatically improve and expedite the drug discovery process. More specifically, your efforts could help them understand how drugs interact with human cells.

This competition will have you disentangling experimental noise from real biological signals. Your entry will classify images of cells under one of 1,108 different genetic perturbations. You can help eliminate the noise introduced by technical execution and environmental variation between experiments.

If successful, you could dramatically improve the industry’s ability to model cellular images according to their relevant biology. In turn, applying AI could greatly decrease the cost of treatments, and ensure these treatments get to patients faster.

This competition is a part of the NeurIPS 2019 competition track. Winners will be invited to contribute their solutions towards the workshop presentation.

Acknowledgments
Thank you to the following sponsors & supporters of this competition:
Google Cloud: Google Cloud is widely recognized as a global leader in delivering a secure, open and intelligent enterprise cloud platform. Our technology is built on Google’s private network and is the product of nearly 20 years of innovation in security, network architecture, collaboration, artificial intelligence and open source software. We offer a simply engineered set of tools and unparalleled technology across Google Cloud Platform and G Suite that help bring people, insights and ideas together. Customers across more than 150 countries trust Google Cloud to modernize their computing environment for today’s digital world.


DoiT: You have the cloud and we have your back. For nearly a decade, we’ve been helping businesses build and scale cloud solutions with our world-class cloud engineering support. We help our customers with technical support and consulting on building and operating complex large-scale distributed systems, developing better machine learning models and setting up big data solutions using Google Cloud, Amazon AWS and Microsoft Azure.


NVIDIA: NVIDIA’s (NASDAQ: NVDA) invention of the GPU in 1999 sparked the growth of the PC gaming market, redefined modern computer graphics and revolutionized parallel computing. More recently, GPU deep learning ignited modern AI — the next era of computing — with the GPU acting as the brain of computers, robots and self-driving cars that can perceive and understand the world. More information at http://nvidianews.nvidia.com.


Lambda: Lambda provides Deep Learning workstations, servers, and GPU cloud services. Lambda Deep Learning infrastructure is used by the world's leading AI research & development organizations including Apple, Microsoft, MIT, Stanford, and the US Government. To learn more, visit www.lambdalabs.com.

Evaluation:

Submissions are evaluated on Multiclass Accuracy, which is simply the average number of observations with the correct label.

Submission File:

For each id_code in the test set, you must predict the correct sirna. The file should contain a header and have the following format:

id_code,sirna

HEPG2-08_1_B03,911

HEPG2-08_1_B04,911

etc.

