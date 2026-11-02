# DSC 180A Methodology Assignment 4

Vishudh Shah  
v8shah@ucsd.edu  
Section: D32, Mentor: Yusu Wang

**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic covered in my domain this quarter has been diffusion models.
I find it interesting that a model can generate a realistic image by starting with random noise and gradually removing it.
Learning about this process has also made me curious about how generation can be guided towards a particular outcome, rather than simply producing a random sample.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I would like to investigate the use of diffusion models for text generation.
Having studied how diffusion models generate images, I am interested in understanding how similar ideas can be applied to language.
In particular, I would like to explore how the noising and denoising processes can be defined for discrete text tokens and whether this approach can offer advantages over autoregressive text generation.

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

Our Quarter 1 project focuses on reproducing results from the EDM paper.
One change I would make is to extend the reproduction with controlled experiments, varying one component at a time, such as the sampling step count or noise schedule.
This would help us understand which choices contribute most to the results and how they affect the tradeoff between image quality and computational cost.
I hope this could also help identify an original research question for Quarter 2, with the long term goal of producing work that could contribute to a publication.

**4. What other techniques would you be interested in using in your project?**

I would be interested in exploring flow matching as another approach to generative modeling and comparing it with diffusion models.
I would also like to investigate guidance methods that steer generated samples towards desired properties.
These could connect to my interest in text generation, where controlling the topic or sentiment of an output would be useful.
