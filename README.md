# Stellar-luminosity

## Andrés Felipe Calderón Ramírez

# 1. Introduction and Motivation

Astronomy is a data-driven science in which relationships between physical quantities are inferred and validated through observation. Classical examples include the relationships between stellar mass, temperature, radius, and luminosity.

In this homework, you will implement **linear regression** and **polynomial regression** from first principles, without using machine-learning libraries.

Rather than calling pre-built fitting routines, you will explicitly define the **hypothesis function**, the **loss function**, and the **optimization algorithm**. The astronomical problem studied here is a simplified stellar luminosity modeling task, inspired by main-sequence behavior: luminosity grows rapidly with mass, and additional properties can introduce nonlinear and interaction effects.

---

# 2. Motivation for Cloud Execution and Enterprise Context

This homework is part of a **four-week Machine Learning Bootcamp** embedded in a course on **Digital Transformation and Enterprise Architecture**. In this context, machine learning is treated as a core architectural capability of modern enterprise systems.

Today, intelligence is increasingly considered a **first-class quality attribute** alongside scalability, availability, security, and performance. Intelligent behavior is no longer confined to offline analytics; it is embedded into platforms, decision-support services, and autonomous or semi-autonomous components.

As enterprise architects, it is not sufficient to understand what models do. We must also understand **how they are built from first principles**, **executed and validated in controlled environments**, and **operated within cloud platforms**.

---

# 3. Dataset and Notation

Use the following notation throughout:

- **M**: stellar mass (in units of solar mass, \( M_\odot \))
- **T**: effective stellar temperature (Kelvin, K)
- **L**: stellar luminosity (in units of solar luminosity, \( L_\odot \))

---

## Part I Dataset (One Feature)

```text
M = [0.6, 0.8, 1.0, 1.2, 1.4, 1.6, 1.8, 2.0, 2.2, 2.4]
L = [0.15, 0.35, 1.00, 2.30, 4.10, 7.00, 11.2, 17.5, 25.0, 35.0]
```
---

## Part II dataset (two features)

```text
M = [0.6, 0.8, 1.0, 1.2, 1.4, 1.6, 1.8, 2.0, 2.2, 2.4]
T = [3800, 4400, 5800, 6400, 6900, 7400, 7900, 8300, 8800, 9200]
L = [0.15, 0.35, 1.00, 2.30, 4.10, 7.00, 11.2, 17.5, 25.0, 35.0]
```

---
## AWS SageMaker Execution Evidence 

## Process:

1. I have started the lab in the AWS academy. 
2. I enter to sagemaker with the user we created in class.
3. In sagemaker I created a new code editor instance.
4. I open the instance and enter to visual studio.
5. I drag the archives form my directory in git hub.
6. I configure the kernel.
7. I compile all the cells in both jupyters.

## Differences between 

### Book 1:

![](img/proof.png)

![](img/1.1.png)

![](img/1.2.png)

![](img/1.3.png)

![](img/1.4.png)

![](img/1.5.1.png)

![](img/1.5.2.png)

![](img/1.6.1.png)

![](img/1.6.2.png)

![](img/1.7.1.png)

![](img/1.7.2.png)

![](img/1.8.1.png)

![](img/1.8.2.png)

![](img/1.8.3.png)

![](img/1.8.4.png)

![](img/1.8.5.png)

![](img/1.8.6.png)

![](img/1.9.1.png)

![](img/1.9.2.png)

![](img/1.9.3.png)

![](img/1.10.png)

### Book 2:

![](img/2.1.png)

![](img/2.2.png)

![](img/2.3.png)

![](img/2.3.2.png)

![](img/2.4.1.png)

![](img/2.4.2.png)

![](img/2.4.3.png)

![](img/2.5.1.png)

![](img/2.5.2.png)

![](img/2.5.3.png)

![](img/2.5.4.png)

![](img/2.5.5.png)

![](img/2.5.6.png)

![](img/2.5.7.png)

![](img/results.png)

![](img/2.6.png)

![](img/2.7.png)
