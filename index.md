# Welcome
## Here, you will know more about me as a programmer
**I am a _gym rat_**
<sup>I am a geeky guy as well</sup>

>I want to be myself at times, and that is a bit difficult when I am here. I aim to explore my career path throughout my life, and I enjoy being who I am as a person, Life is like a box of chocolates to me, every time you open a new path, you are entitled to new beginnings.


Some basic code that I really enjoy as a programmer \
'''


    def extractImagePatchfeature(img, pts, patchSize

    Args:
        img: input image
        pts: detected interest points in the previous step
        patchSize: an odd number indicate patch size
    Return:
        features: a list of image patch features (1-d) for each interest point
    
    #-------------------------------------#
    #         WRITE YOUR CODE HERE        #
    #-------------------------------------#
    box = patchSize//2
    features = []
    for pt in pts:
        x,y = pt
        patch = img[y-box:y+box+1,x-box:x+box+1]
        patch = patch.reshape(-1)
        
        if (patch.shape !=(121,)):
            continue
        #print(patch.shape)
        features.append(patch)

            
    return features
'''
**This is a code when I wrote for CSE 152A creating a 2d window across the image, and extracting image features out of the image**

This site was built using [Doheon Kim's intelligence](https://google.com).

# My Image
![Screenshot of me](Desktop/../Screenshot%202023-04-09%20at%202.52.58%20PM.png)

# Section 1
Connecting the dots and pieces of Section to make it look smarter
These are the section Links I have divided myself into

[Section 1](#section-1)

[About me](#here-you-will-know-more-about-me-as-a-programmer)

[My profile picture](#my-image)

## Relative Links

[Readabout me](README.md)

### Common Programming Languages I am interested in
- C++
- C
- Python
- Java

Top 5 Restaurants around San Diego

1. In-n-out
2. Main Chick
3. Oscar's Mexican Seafood
4. The Taco Stand
5. Jomaru Gamjatang

### Task Lists

- [x] Played UC CUP on Saturday at UCLA
- [ ] Did not do homework for CSE 110 yet
- [ ] E4E project due soon on UDP checkbox
- [x] Secured an Internship at a VC
- [x] stopdatkimmy.github.io performed
  
















