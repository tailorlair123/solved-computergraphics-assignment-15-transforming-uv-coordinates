Download Link: https://assignmentchef.com/product/solved-computergraphics-assignment-15-transforming-uv-coordinates
<br>
<span class="kksr-muted">Rate this product</span>

ransforming UV coordinates

The goal of the application contained in index.html, is to create 4 texture animations representing:

<ol>

 <li>A moving car</li>

 <li>A piece of code scrolling up and down</li>

</ol>

3. A rotating fan

4. A key-frame animation of a flame

In file UVanim.js there are four procedures Anim1(t) … Anim4(t)which receives as parameters a floating point value in the 0…1 range that represents the current time. Each procedure should compute and return the time-dependent transform matrix for the UV coordinates. Please refer to the recording of the corresponding lesson, to have an animated view of the intended result. All the four cases are based on the same texture, shown below:

In the application, the mouse turns the view, and the slider at the bottom of the page can be used to change the animation being displayed. To help you in the creation of objects, it is possible to display a color-coded version of the UV coordinates pressing space. File TextureRef.pdf provides a representation of the texture inside a grid, to help locating the correct UV parameters. Before transformation, the faces of the cube have the texture assigned in the whole range: u=0 on the left, u=1 on the right, v=0 on the bottom and v=1 on the top of the cube.