# Project3

<!-- (This is a comment) INSTRUCTIONS: Go through this page and fill out any **bolded** entries with their correct values.-->

# AND101 Project 3 - AnimalApps

Submitted by: ** Sanjita Pokhrel **

Time spent: **3** hours spent in total

## Summary

**My Application** is an android app that duplicates klima onboarding page.   **Change or add to this description**

If I had to describe this project in three (3) emojis, they would be: ** 😊😊😊 **

## Application Features

<!-- (This is a comment) Please be sure to change the [ ] to [x] for any features you completed.  If a feature is not checked [x], you might miss the points for that item! -->

The following REQUIRED features are completed:

- [ x] Pick an app screenshot to duplicate
  - Be sure to add the screenshot to "Chosen Screenshot" below.
- [ x] Create a runnable app that displays an Animal Version of your chosen screenshot
- [ x] Layout uses one (1) or more ConstraintLayout
- [ x] Layout uses one (1) or more ImageView
- [x ] Layout uses three (3) or more TextViews

The following STRETCH features are implemented:

- [ x] Create a custom-shape Button using Shape Drawables
- [ x] Customize the text fonts by creating new Font Resources
- [ ] Add Tooltips to your Views to help users understand how to navigate the UI
- [ ] Create a second layout, this time for an original, personal app idea

The following EXTRA features are implemented:

- [ ] List anything else that you added to improve the app!

## Chosen Screenshot

I have chosen to duplicate the following layout from the **App Name Here** app:

https://designvault.io/shot/256-2409221713/

## Video Demo

https://www.loom.com/share/4fba5954c4534424abde3110830f96f0?sid=1ce00a95-aec3-4ac9-bdd6-286be3344a2d


GIF created with ** Loom **

<!-- Recommended tools:
- [Kap](https://getkap.co/) for macOS
- [ScreenToGif](https://www.screentogif.com/) for Windows
- [peek](https://github.com/phw/peek) for Linux. -->

## Original App Layout (Optional Stretch Feature)

Here is my entry for the "Create a second layout, this time for an original, personal app idea" stretch feature:

It is for an app that **brief description**.

<img src='http://example.com/link/to/your/image.png' title='Chosen Screenshot' width='' alt='Chosen Screenshot' />

## Notes

<!-- First ImageButton and CheckedTextView -->
<ImageView
    android:id="@+id/imageView"
    android:layout_width="90dp"
    android:layout_height="90dp"
    android:maxHeight="110dp"
    app:layout_constraintBottom_toTopOf="@+id/great_choice"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintVertical_bias="0.773"
    tools:layout_editor_absoluteX="143dp"
    app:srcCompat="@drawable/thumb"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0.5"
    app:layout_constraintStart_toStartOf="parent"
    android:visibility="visible"


    />
<TextView
    android:id="@+id/great_choice"
    android:layout_width="wrap_content"
    android:layout_height="30dp"
    android:text="Great Choice!"
    android:textSize="25sp"
    android:textStyle="bold"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0.389"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintVertical_bias="0.252"
    tools:ignore="MissingPrefix" />

<TextView
    android:id="@+id/text1"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:layout_marginStart="4dp"
    android:layout_marginTop="28dp"
    android:fontFamily="sans-serif-condensed-medium"
    android:text="You will offset your 5.2 ton carbon a\n                       footprint by"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0.325"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toBottomOf="@id/great_choice" />

<LinearLayout
    android:id="@+id/linearLayout1"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:orientation="horizontal"
    app:layout_constraintStart_toStartOf="parent"
    android:layout_marginLeft="30dp"
    app:layout_constraintTop_toBottomOf="@id/text1">

    <!-- <ImageButton
        android:id="@+id/imageButton1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:srcCompat="@android:drawable/checkbox_on_background" /> -->

</LinearLayout>

<!-- Second ImageButton and CheckedTextView -->
<LinearLayout
    android:id="@+id/linearLayout2"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:orientation="horizontal"
    app:layout_constraintStart_toStartOf="parent"
    android:layout_marginLeft="30dp"
    app:layout_constraintTop_toBottomOf="@id/linearLayout1">

    <!--<ImageButton
        android:id="@+id/imageButton2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:srcCompat="@android:drawable/checkbox_on_background" /> -->

</LinearLayout>

<!-- Third ImageButton and CheckedTextView -->

<Button
    android:id="@+id/button"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:background="@color/green"
    android:text="CONFIRM"
    android:textColor="@color/white"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0.445"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintVertical_bias="0.774"

    />

<androidx.appcompat.widget.Toolbar
    android:id="@+id/toolbar"
    android:layout_width="409dp"
    android:layout_height="wrap_content"
    android:background="?attr/colorPrimary"
    android:minHeight="?attr/actionBarSize"
    android:theme="?attr/actionBarTheme"
    tools:layout_editor_absoluteX="1dp"
    tools:layout_editor_absoluteY="1dp"
    android:backgroundTint="@color/l_green"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0.389"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintVertical_bias="0"
    app:layout_constraintTop_toTopOf="parent"/>


<CheckedTextView
    android:id="@+id/checkedTextView4"
    android:layout_width="wrap_content"
    android:layout_height="40dp"
    android:fontFamily="serif-monospace"
    android:text="Providing Cook Stoves"
    android:textSize="17dp"
    android:textStyle="bold"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0.42"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintVertical_bias="0.6" />

<com.google.android.material.floatingactionbutton.FloatingActionButton
    android:id="@+id/floatingActionButton3"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:background="@color/white"
    android:clickable="true"
    android:src="@drawable/food"
    app:backgroundTint="@color/pink"
    app:fabSize="mini"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0.08"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintVertical_bias="0.586"
    tools:srcCompat="@tools:sample/avatars" />

<CheckedTextView
    android:id="@+id/checkedTextView3"
    android:layout_width="wrap_content"
    android:layout_height="40dp"
    android:fontFamily="serif-monospace"
    android:text="Building solar power"
    android:textSize="17dp"
    android:textStyle="bold"
    tools:layout_editor_absoluteX="91dp"
    tools:layout_editor_absoluteY="345dp"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0.399"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintVertical_bias="0.5"
    app:layout_constraintTop_toTopOf="parent"/>

<com.google.android.material.floatingactionbutton.FloatingActionButton
    android:id="@+id/floatingActionButton2"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:clickable="true"
    android:src="@drawable/sun"
    app:backgroundTint="@color/pink"
    app:fabSize="mini"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0.08"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintVertical_bias="0.499"
    tools:srcCompat="@tools:sample/avatars"></com.google.android.material.floatingactionbutton.FloatingActionButton>

<CheckedTextView
    android:id="@+id/checkedTextView2"
    android:layout_width="wrap_content"
    android:layout_height="40dp"
    android:fontFamily="serif-monospace"
    android:text="Planting Trees"
    android:textSize="17dp"
    android:textStyle="bold"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0.307"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintVertical_bias="0.413" />


<com.google.android.material.floatingactionbutton.FloatingActionButton
    android:id="@+id/floatingActionButton1"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:clickable="true"
    android:src="@drawable/sun"
    app:backgroundTint="@color/pink"
    app:fabSize="mini"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0.08"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintVertical_bias="0.413"
    tools:srcCompat="@tools:sample/avatars"></com.google.android.material.floatingactionbutton.FloatingActionButton>

<ImageView
    android:id="@+id/imageView2"
    android:layout_width="70dp"
    android:layout_height="47dp"
    tools:layout_editor_absoluteX="0dp"
    tools:layout_editor_absoluteY="5dp"
    app:srcCompat="@drawable/back"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="0"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintVertical_bias="0"
    app:layout_constraintTop_toTopOf="parent"/>

<ImageView
    android:id="@+id/imageView3"
    android:layout_width="70dp"
    android:layout_height="47dp"
    tools:layout_editor_absoluteX="340dp"
    tools:layout_editor_absoluteY="5dp"
    app:srcCompat="@drawable/cross"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintHorizontal_bias="1"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintVertical_bias="0"
    app:layout_constraintTop_toTopOf="parent"/>

## License

Copyright **yyyy** **your name**

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
