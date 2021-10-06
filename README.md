
readme

# react-native-range-slider-expo
![Supports Android and iOS](https://img.shields.io/badge/platforms-android%20|%20ios-blue.svg) &nbsp;&nbsp;
![MIT License](https://img.shields.io/npm/l/react-native-range-slider-expo?color=red)
### Customizable range slider for react native apps
<br/><br/>
## API - RangeSlider (default import)
| Property | Type | Required | Default |
| :---     |:----:|  :-----: | :-----: | 
| min | number | yes | - |
| max | number | yes | - |
| fromValueOnChange | callback | yes | - |
| toValueOnChange | callback | yes | - |
| step | number | no | 1 |
| styleSize | string ( 'small' \| 'medium' \| 'large' \| number )  | no | 'medium' |
| fromKnobColor | string (color) | no | '#00a2ff' |
| toKnobColor | string (color) | no | '#00a2ff' |
| inRangeBarColor | string (color) | no | 'rgb(100,100,100)' |
| outOfRangeBarColor | string (color) | no | 'rgb(200,200,200)' |
| valueLabelsTextColor | string (color) | no | 'white' |
| valueLabelsBackgroundColor | string (color) | no | '#3a4766' |
| rangeLabelsTextColor | string (color) | no | 'rgb(60,60,60)' |
| showRangeLabels | boolean | no | true |
| showValueLabels | boolean | no | true |
| initialFromValue | number | no | as 'min' value |
| initialToValue | number | no | as 'max' value |

<br/>

## API - Slider (1 knob)
| Property | Type | Required | Default |
| :---     |:----:|  :-----: | :-----: | 
| min | number | yes | - |
| max | number | yes | - |
| valueOnChange | callback | yes | - |
| step | number | no | 1 |
| styleSize | string ( 'small' \| 'medium' \| 'large' \| number )  | no | 'medium' |
| knobColor | string (color) | no | '#00a2ff' |
| inRangeBarColor | string (color) | no | 'rgb(200,200,200)' |
| outOfRangeBarColor | string (color) | no | 'rgb(100,100,100)' |
| valueLabelsTextColor | string (color) | no | 'white' |
| valueLabelsBackgroundColor | string (color) | no | '#3a4766' |
| rangeLabelsTextColor | string (color) | no | 'rgb(60,60,60)' |
| showRangeLabels | boolean | no | true |
| showValueLabels | boolean | no | true |
| initialValue | number | no | as 'min' value |

<br/>

## API - Textual Slider
| Property | Type | Required | Default | 
| :---     |:----:|  :-----: | :-----: | 
| values | [ItemType] | yes | - |
| valueOnChange | callback | yes | - |
| styleSize | string ( 'small' \| 'medium' \| 'large' \| number )  | no | 'medium' |
| knobColor | string (color) | no | '#00a2ff' |
| inRangeBarColor | string (color) | no | 'rgb(200,200,200)' |
| outOfRangeBarColor | string (color) | no | 'rgb(100,100,100)' |
| valueLabelsTextColor | string (color) | no | 'white' |
| valueLabelsBackgroundColor | string (color) | no | '#3a4766' |
| rangeLabelsTextColor | string (color) | no | 'rgb(60,60,60)' |
| showRangeLabels | boolean | no | true |
| showValueLabels | boolean | no | true |
| initialValue | number | no | - |

<br/><br/>

## License
This project is licensed under the MIT License

<br/><br/>

## Todo
   - [X] Add plain slider (with 1 knob)
   - [X] Add initial values
   - [X] Add numeric style size
   - [X] Add textual values
   - [ ] Add prefix/suffix to numeric values
   - [ ] Beautify styling
   <!-- - [ ] Knob is pressed indication -->
   <!-- - [ ] Change value press on bar (on the out of range parts) -->
