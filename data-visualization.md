---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Data Visualization
permalink: data-visualization
order: 3
icon: fa-eye
---

One project I'm passionate about within science is data visualization.  Beyond the importance of <a href='http://www.randalolson.com/2014/06/28/how-to-make-beautiful-data-visualizations-in-python-with-matplotlib/'>making good plots</a>, in neutrino physics the data typcially comes segmented into 'events' - a single readout of the detector.  These 'event' objects really just consist of all the data from the detector within a brief period where something interested happened.

For me, having a way to visualize and interact with single events of data is a crucial and mandatory part of an experimental project in physics.  To that end, I've developed a suite of visualization tools based on <a href='https://riverbankcomputing.com/software/pyqt/intro'>PyQt</a> for window management and <a href='http://www.pyqtgraph.org/'>pyqtgraph</a> for fast, dynamic interactions with data.  Despite starting as a little side project, this has taken a life of it's own as my visualization tools have spread to five different projects, and images made with my software have been popping up across a number of places.

For example, all of the data visualizations on the <a href='http://deeplearnphysics.org/DataChallenge/'>Deep Learn Physics</a> website are made with my visualization software (source code <a href='https://github.com/DeepLearnPhysics/larcv-viewer'>here</a>), as well the images on the Microboone <a href='http://microboone.fnal.gov/'>homepage</a> (<a href='https://github.com/coreyjadams/gallery-framework'>source</a>).

