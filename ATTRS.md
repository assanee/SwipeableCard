##FIELD ATTRIBUTE

|name|format|description|
|:---:|:---:|:---:|
| sc_cardRadius | dimension | Set the radius of Swipeable Card
| sc_animDuration | float | Set the duration time (millis) for animation
| sc_title | string | Set Swipeable Card title
| sc_titleColor | color | Set color of title
| sc_image | integer | Set an image on Swipeable Card
| sc_subTitle | string | Set a sub title
| sc_toolbarColor | color | Set color of toolbar
| sc_text | string | Set a text inside Swipeable Card
| sc_swipeToDismiss | boolean | Set swipe to dismiss feature on Swipeable Card

##USAGE

    <it.michelelacorte.swipeablecard.SwipeableCard
        xmlns:SwipeableCard="http://schemas.android.com/apk/res-auto"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:id="@+id/swipeCard"
        SwipeableCard:sc_animDuration="200"
        SwipeableCard:sc_titleColor="@color/colorPrimary">
        <!-- And so on -->
    </it.michelelacorte.swipeablecard.SwipeableCard>
