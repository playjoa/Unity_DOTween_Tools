# Unity_DOTween_Tools
Make your UI pop with easy to implement animations!

Download <a href='https://assetstore.unity.com/packages/tools/animation/dotween-hotween-v2-27676'>DOTween</a> here!

/DOTween (Folder): Contains the base framework for lean tween! You can also get it for free from the Unity Asset Store <br>
/DOTween Tools (Folder): Contains the 3 scripts to use in your UI, or other areas that you may find it useful in your project :D <br>

# Make your UI Pop!
![](Screenshots/Demo.gif)


## DOTweenListAnim.cs
- Attach to a parent of a list, it will animate each one of the childs in order (from top to bottom)!

### Example: <br>
![](Screenshots/ListAnimator.png)
- Attaching the ListAnimator on "LevelOptions" will animate them in order!
- You can set how long the delay to start animating the childs, delay between childs animation and the duration of the animation!

## DOTweenAnim.cs
- Attach to an object such as a card that holds some info (MeesageBoxes or entire screens), you can also set UnityEvents to happen after close animation!  

### Example: <br>
![](Screenshots/TweenerAnimation.png)
- Set type of open and close animation!
- Set values to your liking!
- To activate close animation reference the TweenerAnimation in your card in a button or script.
- Set to deactivate whatever you want on the close event

## DOTweenPopUp.cs
- Similar to TweenerAnimation, will Open the desired card (Good for notification Pop Ups or DamageTexts) and close after a desired time!

### Example: <br>
![](Screenshots/PopUp.png)
- Set values to your liking and done, the pop up will autodeactivate after close animation!
- OnOpenedPopUp and OnClosedPopUp events.
