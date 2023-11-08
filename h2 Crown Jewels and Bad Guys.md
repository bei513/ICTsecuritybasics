# h2 Assignment
This assignment is part of the Tero Karvinen's course Trust to Blockchain 2023 autumn. (Karvinen 2 November 2023.)

## 1. Intelligence-driven CND, summary
Definitions<br>
APT - advanced persistent threat<br>
CND - computer network defence model<br>

Aim of the article is to give reader understanding what kind of models can be used to defence, how to apply them in intelligence driven CND and explain these through a case study.

 * APT are often successfull due to wrong assumptions
 * Human factor plays decisive role
 * Prevention requires development in analysis, processes and technology
 * Cyber Kill chain model demonstrates 7 steps of the attacks 
 * Kill chain requires success in each step and therefore mitigation in just one chain phase disrupts the attack
 * APT adversaries are patient and calulating and therefore each kill chain phase intrusions must be analyzed carefully to be able to prevent intrusions that might come after months
 * There are several models that can disrupt the kill chain, e.g. IED, ABSAC, SCP and F2T2EA
 * Intelligent CND requires careful mapping and analyzing
(Hutchins, Cloppert & Amin.)

Table 1. Example of intrusion attemp matrix (Hutchins & al.)
![image](https://github.com/bei513/ICTsecuritybasics/assets/149093922/aba4259b-2365-47f5-9290-dd925d549f6e)

## 2. Threat modeling, Chapter 1 summary 
* Thread modeling is helping to find security problems, enhances to see the bigger picture, enhances to prevent problems before they exists and points out threats that might come to your way.
* This chapter provides step by step instuctions of how you can do threat modeling with different tools like Elevation of Privilage game, STRIDE Mnemonic framework or threat modeling of your own
* Provides a checklist to complete the modeling
(Shostack 2014.)

## 3. Installing Debian on virtual box
As a non-technical person, I had no idea what the assignment was. First I started to look the instructions and got totally confused. Couldn't understand what is Debian, what I'm downloading, how to download and what I suppose to do after downloading. Got stuck here as the instructions were really unclear and full of technical vocabulary. In this point I stopped, I was thinking that I am not able to do this with my knowledge. 

Next day I got back to this assignment and now started by reading about Debian and virtual box, so in this point I understood that I am downloading Linux based virtual operating system to work in Windows PC. Live installation image allows this without any changes in hard drive. Got it - now I start to understand assignment a little bit. (Debian 2022 & 2023.)

In this point I looked the assighment (Karvinen 2 November 2023) and Install Debian virtual box instructions (Karvinen 2023) again closely and I realized that I might understand what the task actually is. The day before I had two other course deadlines and obviously my brain was overwhelmed with that. Let's give it a try now.
1. Googling "Debvian ISO image" - first problem appears, do I need to download BitTorrent version or just DVD/USB version. I read BitTorrent link and assume I don't need that. (Debian 6 October 2023). I click the downloading link and get very confused in this point. How to download?? I go back to previous page and start to read instructions again - do I need to download Calamares or Debvian-installer first?
So I went back to knowledge-base. I started to read Debian GNU/Linux Installation Guide (Debian 2023) and finally chapter 1.5 there was a link to distribution page and there I could find downloadable link that was also downloadin. However, this page was outdated and didn't solve the problem. So I went to original English website and downloaded small package from there. In this point I am not at all sure what the heck I am doing... (Debian 6 October 2023.)

Next I unzip the file and open readme.html and readme.mirrors.html. I am not sure if I should do something else but as I don't understand what I am doing I decided to go ahead with next task in assignment - create a new virtual machine. So I downloaded VirtualBox 7.0.12 Windows host package. With a setup I got following error messages. 

![Oracle VM VirtualBox 7 0 12 Setup 8 11 2023 14 56 25](https://github.com/bei513/ICTsecuritybasics/assets/149093922/89736e66-3df6-4b72-a1fe-358d8c2e0380)

![VirtualBox Installer 8 11 2023 14 57 39](https://github.com/bei513/ICTsecuritybasics/assets/149093922/b672067c-cd89-438b-9874-ff930f5bfe4c)

In this point I have 2,5 hours before deadline and I still have thread model tasks to do. I desided to stop in this point and consentrate on next task.

## 4. Imaginary Boogie-man & Threat model
I started by checking how I can make a table at Github. (Github docs 2023.). Decided it's easier to do at excel.

Imaginary situation: Construction company is calculating contract bonuses for workers manually. Sitemanagers are submitting workers hours and assembled rebar kilos manually to excel where is formulas calculating euros for each worker.

![image](https://github.com/bei513/ICTsecuritybasics/assets/149093922/2250cd4a-0a51-4695-9c79-e03dc4314854) <br>
Analyzing the model: <br>
Construcion industry's reporting is still very manual in Finland. Digital transformation would bring a lot of efficiency to the industry and therefore there is a lot of potential for different kind of digitalization projects. Industry also moves around millions of Euros so therefore it is very attractive for intruders. Also, there is a lot of foreign workforse, gray econmy and foreign companies. All these issues are very attractive for frauds and for the criminal hacking. People who are doing the decisions are "Baby boomers" or "Gen X" who don't have that much technical understanding where workers start to be "Millenials" and "Zoomers" who have very good understanding the capabilities and limitations in technology. This allows employees to engage in misconduct without being caught immediately, if at all.


## 5. Incident analysis with cyber kill chain model

## References
Debian CD levyillä. Debianin CD-vedosten imurointi Bittorrentilla. 6 October 2023. URL: https://www.debian.org/CD/torrent-cd/. Accessed: 8 November 2023. 

Debian CD levyillä. VUKK. 6 October 2023. URL: https://www.debian.org/CD/faq/#mailing-list. Accessed: 8 November 2023.

Debian. 4 July 2023. Debianin hankkiminen. URL: https://www.debian.org/distrib/. Accessed: 8 November 2023.

Debian. 6 October 2023. Debian distribution: URL: https://www.debian.org/distrib/index.en.html. Accessed: 8 November 2023.

Debian 2023. GNU/Linux Installation Guide. URL: https://www.debian.org/releases/stable/amd64/index.en.html. Accessed 8 November 2023.

Debian on CDs/DVVs. 19 October 2023. Live install Images. URL: https://www.debian.org/CD/live/. Accessed: 8 November 2023.

Debian. Reasons to Use Debian. 11 February 2022. URL: https://www.debian.org/intro/why_debian. Accessed: 8 November 2023. 

Github docs 2023. Organizing information with tables. URL: https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables. Accessed: 8 November 2023.

Karvinen, T. 2023. Install Debian on Virtualbox - Updated 2023. URL: https://terokarvinen.com/2021/install-debian-on-virtualbox/. Accesed: 8 November 2023. 

Karvinen, T. 2 November 2023. Trust to Blockchain 2023 autumn. Course task page. URL: https://terokarvinen.com/2023/trust-to-blockchain/#h2-crown-jewels-and-bad-guys. Accessed: 6 November 2023.

Hutchins, E. Cloppert, M. Amin, R.  Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains. Lockheed Martin Corporation. URL: https://lockheedmartin.com/content/dam/lockheed-martin/rms/documents/cyber/LM-White-Paper-Intel-Driven-Defense.pdf. Accessed: 6 November 2023.

Shostack, A. February 2014. Threat Modeling: Designing for Security. John Wiley & Sons, Inc. Hoboken, NJ. O'Reilly learning. Accessed: 6 November 2023.
