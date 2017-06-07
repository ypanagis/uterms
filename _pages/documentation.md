---
layout: single
permalink: /documentation/
title: Documentation
---

{% include toc title="Operating uTerms" %}
## Installation
### Windows
Download the `.exe` file from the [Download](/download/) section. Run it and follow the steps. The software gets installed at: `C:\Users\<user_name>\AppData\Local\uTerms`.
### MacOSX
  1. Download the zip file from the [Download](/download/) section.
  2. Unzip it in a folder in your home directory.
  
## Running the software
### Windows
On **Windows 10** your software will be under **Start menu > uTerms.software > uTerms**, or you can press `Windows key + S` and type "uTerms" and Enter.

### MacOSX
**Note:** it is necessary to install the **Java SE Development Kit** before you will be able to run the software. You can find it [here](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html). 
Trust the downloaded .dmg file, Oracle is sufficiently trustworthy!

To run the software for the first time execute the following steps:

  1. In a Mac open the folder that contains the software
  2. Hold the **Ctrl** button, click the file **uTerms.jar** and from the menu that opens select **Open**. The first time you run the software, Mac OS gives you a message that *this is an untrusted application*. 
  Ignore the message and click **Open**. 
  3. It will ask you for your username and password that you use to install applications. Enter both and hit **Ok**.
  4. From this moment you will be able to run your application by double clicking, or Ctrl+click and then **Open**.
  
## Modifying the dictionary
_To be added soon._
## uTerms use
![Example use]({{ "/assets/images/pic1.png" | absolute_url }} "Basic use")

From the user’s perspective, the functionalities of the software are the following. Firstly, the programme imports a contract to be scanned – it can import it either from a file (like a pdf, or docx, or html), if the user has it saved on their computer, or directly from the internet. For the latter, it is sufficient for a user to copy/paste the URL from an internet browser into the software’s bar. A last option is to import the contract to the programme by directly copy/pasting the contents of the contract into the programme’s main window. Then, the user can click “Process” and, as an output, will receive the same document, with highlighted parts of the text, which are potentially unfair contractual clauses. The outcome of this process is presented in Figure 1, where we can see the terms produced as unfair for the case of Google's terms of service.
The highlighted (annotated) parts will be in different colours, each corresponding to a particular class of unfairness (as it stands now, based on the article by [Luzak and Loos](http://link.springer.com/article/10.1007/s10603-015-9303-7), we have 5 such categories: unilateral change, unilateral termination, liability, choice of law and jurisdiction). The colour coding is shown on the right column of Figure 1 under the title “Annotations”. The user might choose to display only a particular type of unfairness (e.g. only choice of law, or choice of law and liability, etc.), depending on the needs. In the example show above the software displays the entire contract. 

![Annotated paragraphs]({{ "/assets/images/pic2.png" | absolute_url }} "Annotated paragraphs")

Moreover, the software can display only the annotated paragraphs. This use mode is displayed in Figure 2. As we can see in both screenshots so far, these results are shown within the programme’s output window. If the user chooses to save the results, they might decide to save them as a pdf or docx document.

![Batch mode]({{ "/assets/images/pic3.png" | absolute_url }} "Compare mode")

Additionally, we have created a functionality that allows comparing several documents at the same time, see Figure 3. In order to do this, the user can again choose a folder containing the chosen documents, or import them directly from the internet. The output will then contain potentially unfair clauses of all the analysed contracts, ordered by the type of unfairness, indicating which terms comes from terms of which service.
