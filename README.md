# HorizontalWheelView
Custom view for user input that models horizontal wheel controller.

![demo gif](http://i.imgur.com/O7cK7Rc.gif)

API
-------

Methods:
```java
void setListener(Listener listener)
void setRadiansAngle(double radians)
void setDegreesAngle(double degrees)
double getRadiansAngle()
double getDegreesAngle()
```

XML-attributes:
* `normalColor` (color)
* `activeColor` (color) 
* `maxVisibleMarks` (integer) must be an odd number >= 3
* `showActiveRange` (boolean)


License
-------

    Copyright 2016 Mykhailo Shchurov

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
