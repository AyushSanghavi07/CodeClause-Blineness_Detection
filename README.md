# CodeClause_Blindness Detection
# By, Somil Doshi

<h1>Solution To Diabetic Retinopathy Detection </h1>
 <h3>
 <ul>
 <li>RED DOTS(microaneurysms)</li>
 <li>YELLOW "FLAKES"</li>
 <li>INCREASE IN BLOOD VESSEL</li>
 </ul>
 </h3>
 <br>
 <h2>DATASET DESCRIPTION</h2>
 You are provided with a large set of high-resolution retina images taken under a variety of imaging conditions. A left and right field is provided for every subject. Images are labeled with a subject id as well as either left or right (e.g. 1_left.jpeg is the left eye of patient id 1).

A clinician has rated the presence of diabetic retinopathy in each image on a scale of 0 to 4, according to the following scale:
 <h3>
 <ol>
 <li>NO DR -"0"</li>
 <li>MILD -"1"</li>
 <li>MODERATE -"2"</li>
 <li>SEVERE -"3"</li>
 <li>PROLIFERATIVE -"4"</li>
 </ol>
 </h3>

Your task is to create an automated analysis system capable of assigning a score based on this scale.

The images in the dataset come from different models and types of cameras, which can affect the visual appearance of left vs. right. Some images are shown as one would see the retina anatomically (macula on the left, optic nerve on the right for the right eye). Others are shown as one would see through a microscope condensing lens (i.e. inverted, as one sees in a typical live eye exam). There are generally two ways to tell if an image is inverted:

It is inverted if the macula (the small dark central area) is slightly higher than the midline through the optic nerve. If the macula is lower than the midline of the optic nerve, it's not inverted.
If there is a notch on the side of the image (square, triangle, or circle) then it's not inverted. If there is no notch, it's inverted.
Like any real-world data set, you will encounter noise in both the images and labels. Images may contain artifacts, be out of focus, underexposed, or overexposed. A major aim of this competition is to develop robust algorithms that can function in the presence of noise and variation.

<h1>Approach To Blindness Detection </h1>
<h3>MODEL :CNN ALGORITHM</h3>
<h3>PLATFORM :GOOGLE COLLAB</h3>
<h3>DATASET :KAGGLE</h3>
