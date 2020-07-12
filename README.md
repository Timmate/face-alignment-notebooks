# face-alignment-notebooks

Notebooks featuring use of the [`face_alignment`][1]  library for processing videos and for obtaining input landmarks for the project [Deep3DFaceReconstruction][2]. Best to view and run these Notebooks in Google Colab as in that case there should not occur any dependency conflicts and installation of all required packages should go smoothly. 

## Description

* #### `face_alignment_for_videos.ipynb`
Performs face alignment (i.e., detection of 68 facial landmarks) on each frame of a given video. For processing a video, `ffmpeg` is used. Related [Colab Notebook][4].

* #### `face_alignment_for_deep3d.ipynb`
Performs face alignment and extracts 5 landmarks needed to run the project Deep3DFaceReconstruction. Related [Colab Notebook][5].

## Acknowledgement

Thanks to [Adrian Bulat][3] for the development of the amazing `face_alignment` library. Also, thanks to the authors of the [Deep3DFaceReconstruction][2] project for making their work publicly available.

[1]: https://github.com/1adrianb/face-alignment
[2]: https://github.com/microsoft/Deep3DFaceReconstruction
[3]: https://github.com/1adrianb
[4]: https://colab.research.google.com/drive/1d4IKoVgFeCFKRfxvrpyZtQDhDS1C3ta2?usp=sharing
[5]: https://colab.research.google.com/drive/18fpjXIXOMSgrq-KCTRkEf83Z1uDLbUGB?usp=sharing
