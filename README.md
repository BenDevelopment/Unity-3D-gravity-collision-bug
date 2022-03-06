# Unity 3D gravity collision bug


When rigidbody objects are falling from high position (300 in my test), the ground collision doesn't works. As you can see in the video, when I change the height to 30, it works.
The spheres have rigidbodies using gravity and a sphere collider.
The grounds have mesh collider for th two on the right, and a box collider for the one on the left.
I've tried to add kinematics rigidbodies to the grounds but it doesn't changes anything.

Using Unity 2020.3.28f1.

The repository is a minimal reproduction.

<figure class="video_container">
  <iframe src="https://youtu.be/vqbo3rweEmA" frameborder="0" allowfullscreen="true"> </iframe>
</figure>

