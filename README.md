This program takes blurry or low-quality images of the back of the eye (called retinal fundus images) and makes them clearer. These images are important for doctors to check eye health, but sometimes they’re hard to read because of lighting issues, blur, or random spots. The program uses a smart computer model (called a neural network) to fix these problems, making the images sharper and easier to analyze. It’s based on a research paper that created a tool called "cofe-Net" to do this.
The program:
1.	Creates fake low-quality versions of clear eye images to practice with.
2.	Trains a model to turn those low-quality images back into clear ones.
3.	Tests the model on a few images and shows you how good the results are with numbers (PSNR and SSIM) and pictures.
