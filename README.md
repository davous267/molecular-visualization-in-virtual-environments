# Molecular Visualization in Immersive Virtual Environments [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of applications focusing on molecular visualization in immersive virtual environments, including augmented, virtual, and mixed reality.  

Created as a part of the publication *State of the Art of Molecular Visualization in Immersive Virtual Environments* submitted to EuroVis 2022.

<!--
# Emoji Labels
Add
-->


# Table of Contents
* [Extensions of Existing Desktop Applications](#desktop-extensions) 
   * [Virtual Reality](#desktop-extensions-vr)
   * [Augmented Reality](#desktop-extensions-ar)
   * [Mixed Reality](#desktop-extensions-mr)
* [Applications Designed Solely for Immersive Devices](#purely-immersive)
    * [Virtual Reality](#purely-immersive-vr)
    * [Augmented Reality](#purely-immersive-ar)
    * [Mixed Reality](#purely-immersive-mr)
* [Building MR Applications](#building-mr-applications)

An important aspect of research in molecular visualization in an immersive virtual environment is the development of software tools and prototypes. Therefore, we also paid attention to the availability of software tools during the literature review. We list the number of tools available and focus on those that can be downloaded and tested. The purpose of this section is to address two types of readers. The first type is the reader who is only interested in the available tools that he can use and test for a specific domain challenge. The second type of reader is interested in developing a prototype for mixed reality molecular visualization. Therefore, we also discuss the options for the interested reader to start these prototypes, as well as the advantages and disadvantages of the available APIs and frameworks. 

We have found that the published work that appeared before the first consumer-grade MR headsets were available mostly used specialized hardware and specialized software, which made it difficult to spread the approach among interested researchers, at least it was only possible in certain niches. Later, the tools became more widely available as it became easier to test them on commonly available hardware, as described in the Hardware section. We found that the tools can be divided into two main categories. The first are extensions of existing desktop tools that provide additional immersive functionality. The second are tools designed exclusively for immersive devices. We encourage readers to take a close look at existing tools and see if certain desired functionality already exists. 

# Extensions of Existing Desktop Applications <a name="desktop-extensions"></a>

Some of the existing molecular visualization tools, such as Chimera and SAMSON Connect and others, have recognized the potential of 3D interaction and viewing. The major advantage of these tools is that they access a large number of features that already exist in desktop tools. Often it is simply the ability to view the molecular scene in an immersive environment, while interactive modeling is only possible on the desktop side. This setup allows for a workflow where the user can take advantage of both modalities, i.e., the desktop tools have been developed over an extended period of time and provide powerful molecular visualization and modeling capabilities that are indirectly accessible from the immersive environment. As mentioned earlier, text input in MR is a major challenge, which would be alleviated by having access to the desktop tool. Currently available desktop tools with MR capabilities are: 

## Virtual Reality <a name="desktop-extensions-vr"></a>
TODO

## Augmented Reality <a name="desktop-extensions-ar"></a>
TODO

## Mixed Reality <a name="desktop-extensions-mr"></a>
TODO

# Applications Designed Solely for Immersive Devices <a name="purely-immersive"></a>

A large number of approaches are being developed as standalone tools. It should be noted that while there are some existing desktop versions, there is no direct connection to the desktop tool and the workflow is mainly facilitated in the immersive environment. Examples of such tools are: 

## Virtual Reality <a name="purely-immersive-vr"></a>
* **Nanome** [[Website](https://nanome.ai/)|[Publication](https://doi.org/10.1016/J.JMGM.2019.03.010)] – Virtual reality software for visualization of molecules, drug discovery, and molecular modeling.

## Augmented Reality <a name="purely-immersive-ar"></a>
TODO

## Mixed Reality <a name="purely-immersive-mr"></a>

# Building MR Applications <a name="building-mr-applications"></a>
In recent literature, we have found that many works use game engines to develop the MR prototypes for their applications. The Unreal and Unity game engines are the most widely used because they provide instant functionality for developing applications with advanced interactions and optimized rendering. Another example is the detached Amazon Lumberyard, which will be extended to the Open 3D Engine. These game engines support common devices and, most importantly, allow ideas to be quickly turned into prototypes. An often cited advantage is also the large, powerful community, support and asset stores.  However, it should be noted that game engines differ greatly in their licensing model, and for projects with a longer-term perspective, the license must be carefully considered. The game engines do not come without limitations. While they are easy to use and the scripting features allow for rapid prototyping, they offer less control over rendering and the general functions of a tool. Here, great flexibility can be provided at the price of more technical effort if the prototype is built from frameworks. Most important here are a graphics API such as OpenGL and DirectX, and an SDK that provides access to immersive hardware, such as OpenVR, OpenXR, and Windows Mixed Reality. 


