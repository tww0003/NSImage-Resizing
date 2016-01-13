# NSImage+Resizing

NSImage category to make resizing and cropping images easy.

# Instructions
Clone the repo and add the files to your project.  
Import the category  
`#import NSImage+Resizing.h`  
To resize an Image:  
`NSImage *resized = [someImage resizeImageToNewSize:NSMakeSize(1024, 500)];`  
To crop an Image:  
`NSImage *cropped = [someImage cropImageToSize:NSMakeSize(1024, 500) fromPoint:NSZeroPoint];`

# License
MIT