Android-ExpandableTextView
==========================
This is a forked version of Cliff's ExpandableTextView library, which adds support for using the `setMaxLines()` method.

Include it in your project using Jitpack:

```
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```

```
dependencies {
	implementation 'com.github.zacharee:Android-ExpandableTextView:Tag'
}
```

Where `Tag` is the latest commit tag (https://jitpack.io/#zacharee/Android-ExpandableTextView/).

The usage is the same as the original library's. Include the ExpandableTextView in your XML:

```
<at.blogc.android.views.ExpandableTextView
	...
	android:maxLines="10"
	/>
```

And expand/collapse in code:

```
if (expandable.isExpanded) {
	expandable.collapse()
else {
	expandable.expand()
}
```

License
=======

    Copyright 2016 Cliff Ophalvens (Blogc.at)

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
