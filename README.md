# SkyVision: Intelligent Systems for Enhancing Situational Awareness for General Aviation Operations
<!-- 
Intro to SkyVision: Short description of who is doing the work, who funded it. Follow with what are the top 3 goals of this initiative. (Big Picture)
-->
"SkyVision" is an effort at the PARALAB at Arizona State University to build machine learning systems designed to improve situational awareness for general aviation pilots. This project is funded by NASA under their University Leadership Initiative (ULI) program. By developing machine learning algorithms and processing large amounts of data, we aim to improve pilot situational awareness with actionable insights. This research initiative takes advantage of the impressive leaps in flight simulation technology, along with the availablility of large terrain and weather databases to develop new methods to achieve improvements in aviation safety. The goals of this repository are the following:
1. Public Contributions: Collection of a large dataset of images from Microsoft Flight Simulator from general aviation aircraft:
2. Open-Sourced machine learning models for aviation safety:
<!-- Contributions instructions -->
## Crowdsourcing Initiative: Flight Simulator Dataset for General Aviation Scene Understanding
### Dataset : Demonstrative Examples 

### Instructions to use the provided addon for data collection
Large datasets can provide great benefits for building powerful machine learning models. However, collecting large, labeled datasets is time-consuming. We provide a simple method to collect and label data to reduce the effort on fellow community-members. A key requirement for building good datasets for machine learning models is to ensure both image and label quality. Please ensure the following while collecting images:
1. Most of the image should contain the outside environment: This means that the image can be taken from a wing-mounted camera configuration or a camera viewpoint placed on the glareshield of the aircraft.
2. Image-labels should not be too far from reality: For instance, we want to avoid labeling an *OVERCAST* sky image as *SCATTERED* or *FEW*. Labeling *BROKEN* as *SCATTERED*, however, is not as bad. Labeling *SCATTERED* as *BROKEN* is even less of a problem. This is because machine learning models for safety-critical applications need to be accurate, but can err on the side of caution. In this case, considering that broken clouds are a far greater threat for GA pilots than scattered clouds, biasing the model to predict more conservatively is not a dealbreaker, but the reverse is certainly a problem.

## Invitations for collaboration on model development and data curation:
We invite fellow flight simmers and researchers who are interested in aviation safety to contribute data, improve upon the dataset categories, and build new models that improves safety outcomes.

