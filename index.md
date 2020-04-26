---
title: "Photoshop Tricks for Beginners"
permalink: /
layout: default
---

# Photoshop Tricks for Beginners
Recently I've been wanting to get more into photography and photo editing. I have some experience with Adobe Lightroom, but not much experience with Adobe Photoshop. I thought now would be the perfect opportunity to watch a tutorial on how to better use Photoshop. The video I watched is called [17 Adobe Photoshop TUTORIALS, TIPS, TRICKS & HACKS For Editing Photos](https://www.youtube.com/watch?v=V8X5FP2RLnI). Here are some really cool tricks that I've learned from the video.

## How to remove things from photos
### Lasso Tool
From this trick I learned that to remove any object from your photo, Content-Aware and the Lasso tool comes in handy. Using the lasso tool, drag your cursor around the object(s) that you want to be removed from the photo. Click "delete" on your keyboard, and then a "Fill" window will pop up. In the "Contents" section of the window, select "Content-Aware" from the dropdown, and click okay. **The objects will be removed!**

### Spot Healing Brush
There are a lot ways to achieve the same effect in Photoshop. For instance, the spot healing brush can remove objects from photos just as easily as the lasso tool because it also has Content-Aware built into it.

**A tip**: *Sometimes using Content-Aware multiple times on the same object gives different results, so you may have to try it multiple times.*

## How to remove things from images when other tools don't work perfectly
### Clone Stamp tool
Using the Clone Stamp tool, hold down option or alt and click to "sample" a texture from the photo, and paint over the area where the object was removed to more accurately match the rest of the photo.

### Layers
Sometimes none of the tools can really conceal the removed object very well, even with the Clone Stamp tool, *especially* if there are a lot of textures and layers in the background of the photo. A solution to removing an object would be:
1. Select another portion of the photo that is either identical or close to the texture of the section with the object you want to conceal
2. Copy and paste, which creates a new layer. With this new layer, you can go to Edit -> Transform -> Flip Horizontally/Vertically, and put new layer on top of the section of the original layer with the object you want to conceal.
3. Then, to make it so the new layer really blends in with the photo, use the eraser tool to erase any parts of the layer that don't fit right.

## How to lighten or darken parts of images
### Lighten
To lighten a part of an image, use the dodge tool and paint the part you want to lighten. 
### Darken
To darken part of an image, use the burn tool paint the part of the image you want to darken.

## How to combine 2 images together
Using the Quick Selection tool, paint the portion of the image you want to select in both images. In one of the images, click Edit -> Copy to copy the portion, and then Edit -> Paste Into to paste the portion into the other image. Because the portion is now its own layer on the other image, the portion can be edited on its own.
### How to get the copied portion from an image to fit with the other image
In order to better fit the copied portion from the other image into the other photo, go to Edit -> Puppet Warp. A large mesh will appear over the portion and you can select points and drag them as you like to fit into the photo.

![Dog saying 'My specialty is roofing'](ps-tutorial.png)

## Dealing with hair on subjects
Outline the subject using the Quick Selection tool or "Select Subject". Then click on "Select and Mask". Choose a background, and then use the Refine Edge Brush tool to paint the outline of the hair so that the texture of the hair is brought back.
### Fixing the outline of the hair
Sometimes after using the Refine Edge Brush, the outline of the hair looks a little strange against certain color backgrounds. There are 2 main ways you can fix the outline of the hair so that it looks more real against all backgrounds. One way is to use the Dodge or Brush tools and paint onto the edges of the hair. Another way is to double click the layer and select "Inner Glow". Change the blend mode to "Mulitiply, change the color to the color of the hair, and play around using the Preview.

## Transform
To freely transform the selected object as you wish, go to Edit -> Free transform. To edit the photo in a specific way, go to Edit -> Transform and choose from specific ways to transform the selection.

## Liquify
There are tools, called Liquify tools, that can be used to edit a subject in an image. A few effects that one might use to edit a subject's face are:
- Pucker tool: makes a feature of the face smaller
- Bloat tool: makes a feature of the face bigger
- Freeze mask tool: prevents another tool from altering a section of the image

### Face Aware Liquify
For those who really want to retouch a subject's face, Face Aware Liquify can be used to edit properties of facial features, such as changing the subject's eye height and width, for instance.

## How to change a color
Go to Window -> Adjustments, which deals with colors and tones. You can play around with the hue and saturation of a photo and the changes will be saved on its own layer. In order to restore the rest of the image (besides the portion of the image that you want to have the changed color) back to its original color, select the areas with the Quick Selection tool and go to Edit -> Fill, and then choose Black or White depending on the general color of the image.

## How to capture multiple phases of a jump in the same photo
Put all images in the same Photoshop document by going to Select All -> Copy -> Paste. Then go to Edit -> Auto Align, click Auto so that all photos are directly on top of each other. Using the erasor tool, find the person who is jumping by brushing over the area you think that they are to reveal the person. **Don't forget to find any shadows too!**
