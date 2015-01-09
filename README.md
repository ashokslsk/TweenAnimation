**Tween Animation**
  Tween Animation takes some parameters such as start value , end value, size , time duration , rotation angle e.t.c and perform the required animation on that object. It can be applied to any type of object. So in order to use this , android has povided us a class called Animation.
  
![screen 1](https://github.com/ashokslsk/TweenAnimation/blob/master/screens/1.png)
![screen 2](https://github.com/ashokslsk/TweenAnimation/blob/master/screens/2.png)

In order to perform animation in android , we are going to call a static function loadAnimation() of the class AnimationUtils. We are going to recieve the result in an instance of Animation Object. Its syntax is as follows:      
           Animation animation = AnimationUtils.loadAnimation(getApplicationContext(), R.anim.myanimation);


**Example**  
The following example demonstrates the use of Animation in android. You would be able to choose different type of animation from the menu and the selected animation will be applied on an imageView on the screen. To experiment with this example , you need to run this on an emulator or an actual device.         


![screen 3](https://github.com/ashokslsk/TweenAnimation/blob/master/screens/3.png)
![screen 4](https://github.com/ashokslsk/TweenAnimation/blob/master/screens/4.png)
