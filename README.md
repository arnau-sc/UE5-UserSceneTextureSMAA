# UE5.5 User Scene Texture SMAA
This is an implementation of Subpixel Morphological Anti Aliasing 1x using the User Scene Texture system in UE5.5 based on the original SMAA implementation: https://github.com/iryoku/smaa

![smaa detail 2](https://github.com/user-attachments/assets/6568dfc8-b4a7-4c45-bb9f-324df2a03bd5)

Requires Unreal Engine 5.5.3

**Limitations:**

 - Absolutely not production ready
 - It has issues with screen percentage, specially going above 100%
 - There is some artifacting that appears on the border pixels of the screen.
 - It is just SMAA 1x, so at the moment its not really built for adding MSAA on top.

