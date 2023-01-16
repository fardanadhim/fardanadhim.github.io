<!DOCTYPE html>
<html class="scroll-smooth">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link href="dist/output.css" rel="stylesheet" />
    <style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');

/*
! tailwindcss v3.0.23 | MIT License | https://tailwindcss.com
*/

/*
1. Prevent padding and border from affecting element width. (https://github.com/mozdevs/cssremedy/issues/4)
2. Allow adding a border to an element by just adding a border-width. (https://github.com/tailwindcss/tailwindcss/pull/116)
*/

*,
::before,
::after {
  box-sizing: border-box;
  /* 1 */
  border-width: 0;
  /* 2 */
  border-style: solid;
  /* 2 */
  border-color: #e5e7eb;
  /* 2 */
}

::before,
::after {
  --tw-content: '';
}

/*
1. Use a consistent sensible line-height in all browsers.
2. Prevent adjustments of font size after orientation changes in iOS.
3. Use a more readable tab size.
4. Use the user's configured `sans` font-family by default.
*/

html {
  line-height: 1.5;
  /* 1 */
  -webkit-text-size-adjust: 100%;
  /* 2 */
  -moz-tab-size: 4;
  /* 3 */
  -o-tab-size: 4;
     tab-size: 4;
  /* 3 */
  font-family: ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  /* 4 */
}

/*
1. Remove the margin in all browsers.
2. Inherit line-height from `html` so users can set them as a class directly on the `html` element.
*/

body {
  margin: 0;
  /* 1 */
  line-height: inherit;
  /* 2 */
}

/*
1. Add the correct height in Firefox.
2. Correct the inheritance of border color in Firefox. (https://bugzilla.mozilla.org/show_bug.cgi?id=190655)
3. Ensure horizontal rules are visible by default.
*/

hr {
  height: 0;
  /* 1 */
  color: inherit;
  /* 2 */
  border-top-width: 1px;
  /* 3 */
}

/*
Add the correct text decoration in Chrome, Edge, and Safari.
*/

abbr:where([title]) {
  -webkit-text-decoration: underline dotted;
          text-decoration: underline dotted;
}

/*
Remove the default font size and weight for headings.
*/

h1,
h2,
h3,
h4,
h5,
h6 {
  font-size: inherit;
  font-weight: inherit;
}

/*
Reset links to optimize for opt-in styling instead of opt-out.
*/

a {
  color: inherit;
  text-decoration: inherit;
}

/*
Add the correct font weight in Edge and Safari.
*/

b,
strong {
  font-weight: bolder;
}

/*
1. Use the user's configured `mono` font family by default.
2. Correct the odd `em` font sizing in all browsers.
*/

code,
kbd,
samp,
pre {
  font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
  /* 1 */
  font-size: 1em;
  /* 2 */
}

/*
Add the correct font size in all browsers.
*/

small {
  font-size: 80%;
}

/*
Prevent `sub` and `sup` elements from affecting the line height in all browsers.
*/

sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}

sub {
  bottom: -0.25em;
}

sup {
  top: -0.5em;
}

/*
1. Remove text indentation from table contents in Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=999088, https://bugs.webkit.org/show_bug.cgi?id=201297)
2. Correct table border color inheritance in all Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=935729, https://bugs.webkit.org/show_bug.cgi?id=195016)
3. Remove gaps between table borders by default.
*/

table {
  text-indent: 0;
  /* 1 */
  border-color: inherit;
  /* 2 */
  border-collapse: collapse;
  /* 3 */
}

/*
1. Change the font styles in all browsers.
2. Remove the margin in Firefox and Safari.
3. Remove default padding in all browsers.
*/

button,
input,
optgroup,
select,
textarea {
  font-family: inherit;
  /* 1 */
  font-size: 100%;
  /* 1 */
  line-height: inherit;
  /* 1 */
  color: inherit;
  /* 1 */
  margin: 0;
  /* 2 */
  padding: 0;
  /* 3 */
}

/*
Remove the inheritance of text transform in Edge and Firefox.
*/

button,
select {
  text-transform: none;
}

/*
1. Correct the inability to style clickable types in iOS and Safari.
2. Remove default button styles.
*/

button,
[type='button'],
[type='reset'],
[type='submit'] {
  -webkit-appearance: button;
  /* 1 */
  background-color: transparent;
  /* 2 */
  background-image: none;
  /* 2 */
}

/*
Use the modern Firefox focus style for all focusable elements.
*/

:-moz-focusring {
  outline: auto;
}

/*
Remove the additional `:invalid` styles in Firefox. (https://github.com/mozilla/gecko-dev/blob/2f9eacd9d3d995c937b4251a5557d95d494c9be1/layout/style/res/forms.css#L728-L737)
*/

:-moz-ui-invalid {
  box-shadow: none;
}

/*
Add the correct vertical alignment in Chrome and Firefox.
*/

progress {
  vertical-align: baseline;
}

/*
Correct the cursor style of increment and decrement buttons in Safari.
*/

::-webkit-inner-spin-button,
::-webkit-outer-spin-button {
  height: auto;
}

/*
1. Correct the odd appearance in Chrome and Safari.
2. Correct the outline style in Safari.
*/

[type='search'] {
  -webkit-appearance: textfield;
  /* 1 */
  outline-offset: -2px;
  /* 2 */
}

/*
Remove the inner padding in Chrome and Safari on macOS.
*/

::-webkit-search-decoration {
  -webkit-appearance: none;
}

/*
1. Correct the inability to style clickable types in iOS and Safari.
2. Change font properties to `inherit` in Safari.
*/

::-webkit-file-upload-button {
  -webkit-appearance: button;
  /* 1 */
  font: inherit;
  /* 2 */
}

/*
Add the correct display in Chrome and Safari.
*/

summary {
  display: list-item;
}

/*
Removes the default spacing and border for appropriate elements.
*/

blockquote,
dl,
dd,
h1,
h2,
h3,
h4,
h5,
h6,
hr,
figure,
p,
pre {
  margin: 0;
}

fieldset {
  margin: 0;
  padding: 0;
}

legend {
  padding: 0;
}

ol,
ul,
menu {
  list-style: none;
  margin: 0;
  padding: 0;
}

/*
Prevent resizing textareas horizontally by default.
*/

textarea {
  resize: vertical;
}

/*
1. Reset the default placeholder opacity in Firefox. (https://github.com/tailwindlabs/tailwindcss/issues/3300)
2. Set the default placeholder color to the user's configured gray 400 color.
*/

input::-moz-placeholder, textarea::-moz-placeholder {
  opacity: 1;
  /* 1 */
  color: #9ca3af;
  /* 2 */
}

input:-ms-input-placeholder, textarea:-ms-input-placeholder {
  opacity: 1;
  /* 1 */
  color: #9ca3af;
  /* 2 */
}

input::placeholder,
textarea::placeholder {
  opacity: 1;
  /* 1 */
  color: #9ca3af;
  /* 2 */
}

/*
Set the default cursor for buttons.
*/

button,
[role="button"] {
  cursor: pointer;
}

/*
Make sure disabled buttons don't get the pointer cursor.
*/

:disabled {
  cursor: default;
}

/*
1. Make replaced elements `display: block` by default. (https://github.com/mozdevs/cssremedy/issues/14)
2. Add `vertical-align: middle` to align replaced elements more sensibly by default. (https://github.com/jensimmons/cssremedy/issues/14#issuecomment-634934210)
   This can trigger a poorly considered lint error in some tools but is included by design.
*/

img,
svg,
video,
canvas,
audio,
iframe,
embed,
object {
  display: block;
  /* 1 */
  vertical-align: middle;
  /* 2 */
}

/*
Constrain images and videos to the parent width and preserve their intrinsic aspect ratio. (https://github.com/mozdevs/cssremedy/issues/14)
*/

img,
video {
  max-width: 100%;
  height: auto;
}

/*
Ensure the default browser behavior of the `hidden` attribute.
*/

[hidden] {
  display: none;
}

*, ::before, ::after{
  --tw-translate-x: 0;
  --tw-translate-y: 0;
  --tw-rotate: 0;
  --tw-skew-x: 0;
  --tw-skew-y: 0;
  --tw-scale-x: 1;
  --tw-scale-y: 1;
  --tw-pan-x:  ;
  --tw-pan-y:  ;
  --tw-pinch-zoom:  ;
  --tw-scroll-snap-strictness: proximity;
  --tw-ordinal:  ;
  --tw-slashed-zero:  ;
  --tw-numeric-figure:  ;
  --tw-numeric-spacing:  ;
  --tw-numeric-fraction:  ;
  --tw-ring-inset:  ;
  --tw-ring-offset-width: 0px;
  --tw-ring-offset-color: #fff;
  --tw-ring-color: rgb(59 130 246 / 0.5);
  --tw-ring-offset-shadow: 0 0 #0000;
  --tw-ring-shadow: 0 0 #0000;
  --tw-shadow: 0 0 #0000;
  --tw-shadow-colored: 0 0 #0000;
  --tw-blur:  ;
  --tw-brightness:  ;
  --tw-contrast:  ;
  --tw-grayscale:  ;
  --tw-hue-rotate:  ;
  --tw-invert:  ;
  --tw-saturate:  ;
  --tw-sepia:  ;
  --tw-drop-shadow:  ;
  --tw-backdrop-blur:  ;
  --tw-backdrop-brightness:  ;
  --tw-backdrop-contrast:  ;
  --tw-backdrop-grayscale:  ;
  --tw-backdrop-hue-rotate:  ;
  --tw-backdrop-invert:  ;
  --tw-backdrop-opacity:  ;
  --tw-backdrop-saturate:  ;
  --tw-backdrop-sepia:  ;
}

.container{
  width: 100%;
  margin-right: auto;
  margin-left: auto;
  padding-right: 16px;
  padding-left: 16px;
}

@media (min-width: 640px){
  .container{
    max-width: 640px;
  }
}

@media (min-width: 768px){
  .container{
    max-width: 768px;
  }
}

@media (min-width: 1024px){
  .container{
    max-width: 1024px;
  }
}

@media (min-width: 1280px){
  .container{
    max-width: 1280px;
  }
}

@media (min-width: 1320px){
  .container{
    max-width: 1320px;
  }
}

.absolute{
  position: absolute;
}

.relative{
  position: relative;
}

.top-0{
  top: 0px;
}

.left-0{
  left: 0px;
}

.right-4{
  right: 1rem;
}

.top-1\/2{
  top: 50%;
}

.top-full{
  top: 100%;
}

.bottom-0{
  bottom: 0px;
}

.left-1\/2{
  left: 50%;
}

.z-10{
  z-index: 10;
}

.-z-10{
  z-index: -10;
}

.my-2{
  margin-top: 0.5rem;
  margin-bottom: 0.5rem;
}

.mx-8{
  margin-left: 2rem;
  margin-right: 2rem;
}

.mx-auto{
  margin-left: auto;
  margin-right: auto;
}

.mx-3{
  margin-left: 0.75rem;
  margin-right: 0.75rem;
}

.mx-4{
  margin-left: 1rem;
  margin-right: 1rem;
}

.mb-3{
  margin-bottom: 0.75rem;
}

.mt-1{
  margin-top: 0.25rem;
}

.mb-5{
  margin-bottom: 1.25rem;
}

.mb-11{
  margin-bottom: 2.75rem;
}

.mt-12{
  margin-top: 3rem;
}

.mb-8{
  margin-bottom: 2rem;
}

.mb-4{
  margin-bottom: 1rem;
}

.mb-6{
  margin-bottom: 1.5rem;
}

.mr-3{
  margin-right: 0.75rem;
}

.mb-16{
  margin-bottom: 4rem;
}

.mb-2{
  margin-bottom: 0.5rem;
}

.mb-12{
  margin-bottom: 3rem;
}

.mt-5{
  margin-top: 1.25rem;
}

.mb-10{
  margin-bottom: 2.5rem;
}

.mt-2{
  margin-top: 0.5rem;
}

.mb-1{
  margin-bottom: 0.25rem;
}

.mb-9{
  margin-bottom: 2.25rem;
}

.mb-14{
  margin-bottom: 3.5rem;
}

.mt-10{
  margin-top: 2.5rem;
}

.block{
  display: block;
}

.inline-block{
  display: inline-block;
}

.flex{
  display: flex;
}

.hidden{
  display: none;
}

.h-\[2px\]{
  height: 2px;
}

.h-9{
  height: 2.25rem;
}

.h-32{
  height: 8rem;
}

.w-full{
  width: 100%;
}

.w-\[30px\]{
  width: 30px;
}

.w-9{
  width: 2.25rem;
}

.w-60{
  width: 15rem;
}

.max-w-full{
  max-width: 100%;
}

.max-w-\[250px\]{
  max-width: 250px;
}

.max-w-lg{
  max-width: 32rem;
}

.max-w-md{
  max-width: 28rem;
}

.max-w-xl{
  max-width: 36rem;
}

.max-w-2xl{
  max-width: 42rem;
}

.max-w-\[120px\]{
  max-width: 120px;
}

.origin-top-right{
  transform-origin: top right;
}

.origin-bottom-right{
  transform-origin: bottom right;
}

.-translate-y-1\/2{
  --tw-translate-y: -50%;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.-translate-x-1\/2{
  --tw-translate-x: -50%;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.transform{
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.flex-wrap{
  flex-wrap: wrap;
}

.items-center{
  align-items: center;
}

.justify-start{
  justify-content: flex-start;
}

.justify-center{
  justify-content: center;
}

.justify-between{
  justify-content: space-between;
}

.justify-evenly{
  justify-content: space-evenly;
}

.self-end{
  align-self: flex-end;
}

.self-center{
  align-self: center;
}

.overflow-hidden{
  overflow: hidden;
}

.scroll-smooth{
  scroll-behavior: smooth;
}

.truncate{
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

.rounded-lg{
  border-radius: 0.5rem;
}

.rounded-full{
  border-radius: 9999px;
}

.rounded-md{
  border-radius: 0.375rem;
}

.rounded-xl{
  border-radius: 0.75rem;
}

.border{
  border-width: 1px;
}

.border-t{
  border-top-width: 1px;
}

.border-slate-300{
  --tw-border-opacity: 1;
  border-color: rgb(203 213 225 / var(--tw-border-opacity));
}

.border-slate-500{
  --tw-border-opacity: 1;
  border-color: rgb(100 116 139 / var(--tw-border-opacity));
}

.border-slate-800{
  --tw-border-opacity: 1;
  border-color: rgb(30 41 59 / var(--tw-border-opacity));
}

.border-slate-700{
  --tw-border-opacity: 1;
  border-color: rgb(51 65 85 / var(--tw-border-opacity));
}

.bg-transparent{
  background-color: transparent;
}

.bg-slate-900{
  --tw-bg-opacity: 1;
  background-color: rgb(15 23 42 / var(--tw-bg-opacity));
}

.bg-white{
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
}

.bg-teal-500{
  --tw-bg-opacity: 1;
  background-color: rgb(20 184 166 / var(--tw-bg-opacity));
}

.bg-slate-100{
  --tw-bg-opacity: 1;
  background-color: rgb(241 245 249 / var(--tw-bg-opacity));
}

.bg-red-300{
  --tw-bg-opacity: 1;
  background-color: rgb(252 165 165 / var(--tw-bg-opacity));
}

.bg-slate-800{
  --tw-bg-opacity: 1;
  background-color: rgb(30 41 59 / var(--tw-bg-opacity));
}

.bg-slate-700{
  --tw-bg-opacity: 1;
  background-color: rgb(51 65 85 / var(--tw-bg-opacity));
}

.bg-slate-300{
  --tw-bg-opacity: 1;
  background-color: rgb(203 213 225 / var(--tw-bg-opacity));
}

.bg-slate-600{
  --tw-bg-opacity: 1;
  background-color: rgb(71 85 105 / var(--tw-bg-opacity));
}

.bg-slate-200{
  --tw-bg-opacity: 1;
  background-color: rgb(226 232 240 / var(--tw-bg-opacity));
}

.bg-red-400{
  --tw-bg-opacity: 1;
  background-color: rgb(248 113 113 / var(--tw-bg-opacity));
}

.bg-red-500{
  --tw-bg-opacity: 1;
  background-color: rgb(239 68 68 / var(--tw-bg-opacity));
}

.fill-current{
  fill: currentColor;
}

.p-3{
  padding: 0.75rem;
}

.p-6{
  padding: 1.5rem;
}

.px-4{
  padding-left: 1rem;
  padding-right: 1rem;
}

.py-6{
  padding-top: 1.5rem;
  padding-bottom: 1.5rem;
}

.px-3{
  padding-left: 0.75rem;
  padding-right: 0.75rem;
}

.py-2{
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
}

.py-5{
  padding-top: 1.25rem;
  padding-bottom: 1.25rem;
}

.py-3{
  padding-top: 0.75rem;
  padding-bottom: 0.75rem;
}

.px-8{
  padding-left: 2rem;
  padding-right: 2rem;
}

.py-4{
  padding-top: 1rem;
  padding-bottom: 1rem;
}

.py-8{
  padding-top: 2rem;
  padding-bottom: 2rem;
}

.px-6{
  padding-left: 1.5rem;
  padding-right: 1.5rem;
}

.py-20{
  padding-top: 5rem;
  padding-bottom: 5rem;
}

.pt-36{
  padding-top: 9rem;
}

.pb-32{
  padding-bottom: 8rem;
}

.pt-32{
  padding-top: 8rem;
}

.pb-16{
  padding-bottom: 4rem;
}

.pt-20{
  padding-top: 5rem;
}

.pb-\[250px\]{
  padding-bottom: 250px;
}

.pb-20{
  padding-bottom: 5rem;
}

.pb-36{
  padding-bottom: 9rem;
}

.pb-28{
  padding-bottom: 7rem;
}

.pt-24{
  padding-top: 15px;
}

.pb-12{
  padding-bottom: 3rem;
}

.pt-10{
  padding-top: 2.5rem;
}

.text-center{
  text-align: center;
}

.text-lg{
  font-size: 1.125rem;
  line-height: 1.75rem;
}

.text-base{
  font-size: 1rem;
  line-height: 1.5rem;
}

.text-4xl{
  font-size: 2.25rem;
  line-height: 2.5rem;
}

.text-3xl{
  font-size: 1.875rem;
  line-height: 2.25rem;
}

.text-2xl{
  font-size: 1.5rem;
  line-height: 2rem;
}

.text-xl{
  font-size: 1.25rem;
  line-height: 1.75rem;
}

.text-sm{
  font-size: 0.875rem;
  line-height: 1.25rem;
}

.font-bold{
  font-weight: 700;
}

.font-semibold{
  font-weight: 600;
}

.font-medium{
  font-weight: 500;
}

.uppercase{
  text-transform: uppercase;
}

.leading-relaxed{
  line-height: 1.625;
}

.leading-tight{
  line-height: 1.25;
}

.tracking-normal{
  letter-spacing: 0em;
}

.tracking-wide{
  letter-spacing: 0.025em;
}

.tracking-wider{
  letter-spacing: 0.05em;
}

.text-teal-500{
  --tw-text-opacity: 1;
  color: rgb(20 184 166 / var(--tw-text-opacity));
}

.text-slate-900{
  --tw-text-opacity: 1;
  color: rgb(15 23 42 / var(--tw-text-opacity));
}

.text-slate-500{
  --tw-text-opacity: 1;
  color: rgb(100 116 139 / var(--tw-text-opacity));
}

.text-slate-400{
  --tw-text-opacity: 1;
  color: rgb(148 163 184 / var(--tw-text-opacity));
}

.text-slate-800{
  --tw-text-opacity: 1;
  color: rgb(30 41 59 / var(--tw-text-opacity));
}

.text-white{
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.text-slate-300{
  --tw-text-opacity: 1;
  color: rgb(203 213 225 / var(--tw-text-opacity));
}

.text-slate-600{
  --tw-text-opacity: 1;
  color: rgb(71 85 105 / var(--tw-text-opacity));
}

.text-slate-100{
  --tw-text-opacity: 1;
  color: rgb(241 245 249 / var(--tw-text-opacity));
}

.text-slate-200{
  --tw-text-opacity: 1;
  color: rgb(226 232 240 / var(--tw-text-opacity));
}

.text-blue-500{
  --tw-text-opacity: 1;
  color: rgb(59 130 246 / var(--tw-text-opacity));
}

.text-sky-500{
  --tw-text-opacity: 1;
  color: rgb(14 165 233 / var(--tw-text-opacity));
}

.text-pink-500{
  --tw-text-opacity: 1;
  color: rgb(236 72 153 / var(--tw-text-opacity));
}

.underline{
  -webkit-text-decoration-line: underline;
          text-decoration-line: underline;
}

.opacity-60{
  opacity: 0.6;
}

.shadow-lg{
  --tw-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
  --tw-shadow-colored: 0 10px 15px -3px var(--tw-shadow-color), 0 4px 6px -4px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}

.shadow-sm{
  --tw-shadow: 0 1px 2px 0 rgb(0 0 0 / 0.05);
  --tw-shadow-colored: 0 1px 2px 0 var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}

.grayscale-0{
  --tw-grayscale: grayscale(0);
  filter: var(--tw-blur) var(--tw-brightness) var(--tw-contrast) var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate) var(--tw-sepia) var(--tw-drop-shadow);
}

.grayscale{
  --tw-grayscale: grayscale(100%);
  filter: var(--tw-blur) var(--tw-brightness) var(--tw-contrast) var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate) var(--tw-sepia) var(--tw-drop-shadow);
}

.transition{
  transition-property: color, background-color, border-color, fill, stroke, opacity, box-shadow, transform, filter, -webkit-text-decoration-color, -webkit-backdrop-filter;
  transition-property: color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter;
  transition-property: color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter, -webkit-text-decoration-color, -webkit-backdrop-filter;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 150ms;
}

.duration-500{
  transition-duration: 500ms;
}

.duration-300{
  transition-duration: 300ms;
}

.ease-in-out{
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

body {
  font-family: 'Inter', sans-serif;
}

.navbar-fixed{
  position: fixed;
  z-index: 9999;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
  --tw-bg-opacity: 0.8;
  transition-property: color, background-color, border-color, fill, stroke, opacity, box-shadow, transform, filter, -webkit-text-decoration-color, -webkit-backdrop-filter;
  transition-property: color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter;
  transition-property: color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter, -webkit-text-decoration-color, -webkit-backdrop-filter;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 500ms;
  -webkit-backdrop-filter: blur(5px);
          backdrop-filter: blur(5px);
  box-shadow: inset 0 -1px 0 0 rgba(0, 0, 0, 0.1);
}

.hamburger-active > span:nth-child(1){
  --tw-translate-y: -1px;
  --tw-rotate: -45deg;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.hamburger-active > span:nth-child(2){
  --tw-scale-x: 0;
  --tw-scale-y: 0;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.hamburger-active > span:nth-child(3){
  --tw-rotate: 45deg;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

/* .hamburger-active > span:nth-child(3) {
  @apply rotate-[135deg] top-[-10px] transition duration-300;
} */

.hover\:border-teal-500:hover{
  --tw-border-opacity: 1;
  border-color: rgb(20 184 166 / var(--tw-border-opacity));
}

.hover\:bg-teal-400:hover{
  --tw-bg-opacity: 1;
  background-color: rgb(45 212 191 / var(--tw-bg-opacity));
}

.hover\:bg-teal-500:hover{
  --tw-bg-opacity: 1;
  background-color: rgb(20 184 166 / var(--tw-bg-opacity));
}

.hover\:text-white:hover{
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.hover\:text-teal-500:hover{
  --tw-text-opacity: 1;
  color: rgb(20 184 166 / var(--tw-text-opacity));
}

.hover\:no-underline:hover{
  -webkit-text-decoration-line: none;
          text-decoration-line: none;
}

.hover\:opacity-100:hover{
  opacity: 1;
}

.hover\:shadow-lg:hover{
  --tw-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
  --tw-shadow-colored: 0 10px 15px -3px var(--tw-shadow-color), 0 4px 6px -4px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}

.hover\:grayscale:hover{
  --tw-grayscale: grayscale(100%);
  filter: var(--tw-blur) var(--tw-brightness) var(--tw-contrast) var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate) var(--tw-sepia) var(--tw-drop-shadow);
}

.hover\:grayscale-0:hover{
  --tw-grayscale: grayscale(0);
  filter: var(--tw-blur) var(--tw-brightness) var(--tw-contrast) var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate) var(--tw-sepia) var(--tw-drop-shadow);
}

.focus\:outline-none:focus{
  outline: 2px solid transparent;
  outline-offset: 2px;
}

.group:hover .group-hover\:text-teal-500{
  --tw-text-opacity: 1;
  color: rgb(20 184 166 / var(--tw-text-opacity));
}

@media (min-width: 640px){
  .sm\:text-4xl{
    font-size: 2.25rem;
    line-height: 2.5rem;
  }
}

@media (min-width: 768px){
  .md\:w-1\/2{
    width: 50%;
  }

  .md\:w-12{
    width: 3rem;
  }

  .md\:w-4\/12{
    width: 33.333333%;
  }

  .md\:w-1\/3{
    width: 33.333333%;
  }

  .md\:scale-125{
    --tw-scale-x: 1.25;
    --tw-scale-y: 1.25;
    transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
  }

  .md\:text-xl{
    font-size: 1.25rem;
    line-height: 1.75rem;
  }

  .md\:text-5xl{
    font-size: 3rem;
    line-height: 1;
  }

  .md\:text-4xl{
    font-size: 2.25rem;
    line-height: 2.5rem;
  }

  .md\:text-lg{
    font-size: 1.125rem;
    line-height: 1.75rem;
  }
}

@media (min-width: 1024px){
  .lg\:static{
    position: static;
  }

  .lg\:right-0{
    right: 0px;
  }

  .lg\:mx-6{
    margin-left: 1.5rem;
    margin-right: 1.5rem;
  }

  .lg\:mr-0{
    margin-right: 0px;
  }

  .lg\:mt-0{
    margin-top: 0px;
  }

  .lg\:ml-8{
    margin-left: 2rem;
  }

  .lg\:block{
    display: block;
  }

  .lg\:flex{
    display: flex;
  }

  .lg\:inline-flex{
    display: inline-flex;
  }

  .lg\:hidden{
    display: none;
  }

  .lg\:w-full{
    width: 100%;
  }

  .lg\:w-1\/2{
    width: 50%;
  }

  .lg\:w-1\/3{
    width: 33.333333%;
  }

  .lg\:w-2\/3{
    width: 66.666667%;
  }

  .lg\:w-4\/12{
    width: 33.333333%;
  }

  .lg\:max-w-full{
    max-width: 100%;
  }

  .lg\:bg-red-500{
    --tw-bg-opacity: 1;
    background-color: rgb(239 68 68 / var(--tw-bg-opacity));
  }

  .lg\:bg-transparent{
    background-color: transparent;
  }

  .lg\:py-0{
    padding-top: 0px;
    padding-bottom: 0px;
  }

  .lg\:px-6{
    padding-left: 1.5rem;
    padding-right: 1.5rem;
  }

  .lg\:py-6{
    padding-top: 1.5rem;
    padding-bottom: 1.5rem;
  }

  .lg\:px-0{
    padding-left: 0px;
    padding-right: 0px;
  }

  .lg\:pt-24{
    padding-top: 6rem;
  }

  .lg\:pt-10{
    padding-top: 2.5rem;
  }

  .lg\:text-xl{
    font-size: 1.25rem;
    line-height: 1.75rem;
  }

  .lg\:text-5xl{
    font-size: 3rem;
    line-height: 1;
  }

  .lg\:text-2xl{
    font-size: 1.5rem;
    line-height: 2rem;
  }

  .lg\:text-4xl{
    font-size: 2.25rem;
    line-height: 2.5rem;
  }

  .lg\:text-lg{
    font-size: 1.125rem;
    line-height: 1.75rem;
  }

  .lg\:text-3xl{
    font-size: 1.875rem;
    line-height: 2.25rem;
  }

  .lg\:shadow-none{
    --tw-shadow: 0 0 #0000;
    --tw-shadow-colored: 0 0 #0000;
    box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
  }
}

@media (min-width: 1280px){
  .xl\:mx-8{
    margin-left: 2rem;
    margin-right: 2rem;
  }

  .xl\:w-10\/12{
    width: 83.333333%;
  }

  .xl\:w-1\/3{
    width: 33.333333%;
  }
}
.anjayy{
  --tw-bg-opacity: 1;
  background-color: rgb(15 23 42 / var(--tw-bg-opacity));
   
}
.putihs{
  color:#fff;
}
.pt-98{
  padding-top: 3rem;
}
.pb-3200{
  padding-bottom: 3rem;
}

    </style>
  </head>
  <body>
    <!-- Header Start -->
    <header class="bg-transparent absolute top-0 left-0 z-10 w-full flex items-center transition duration-500">
      <div class="container">
        <div class="flex items-center justify-between relative">
          <div class="px-4 max-w-full">
            <a href="#hero" class="font-bold text-lg text-teal-500 block w-full py-6">Sandhika Galih</a>
          </div>
          <div class="flex px-4 justify-between items-center">
            <div>
              <button id="hamburger" name="hamburger" class="block absolute right-4 top-1/2 -translate-y-1/2 px-3 py-2 rounded-lg lg:hidden">
                <span class="relative w-[30px] h-[2px] my-2 block bg-slate-900 transition duration-300 origin-top-right"></span>
                <span class="relative w-[30px] h-[2px] my-2 block bg-slate-900 transition duration-300"></span>
                <span class="relative w-[30px] h-[2px] my-2 block bg-slate-900 transition duration-500 origin-bottom-right"></span>
              </button>

              <nav
                id="nav-menu"
                class="absolute py-5 bg-white shadow-lg rounded-lg max-w-[250px] w-full right-4 top-full hidden lg:block lg:static lg:bg-transparent lg:max-w-full lg:py-0 lg:px-6 lg:shadow-none"
              >
                <ul class="block lg:flex">
                  <li class="group relative">
                    <a href="#hero" class="text-base text-slate-900 py-2 mx-8 flex group-hover:text-teal-500 lg:inline-flex lg:py-6 lg:px-0 lg:mr-0">Beranda</a>
                  </li>
                  <li class="group">
                    <a href="#about" class="text-base text-slate-900 py-2 mx-8 flex group-hover:text-teal-500 lg:inline-flex lg:py-6 lg:px-0 lg:mr-0 lg:ml-8">Tentang Saya</a>
                  </li>
                  <li class="group">
                    <a href="#portfolio" class="text-base text-slate-900 py-2 mx-8 flex group-hover:text-teal-500 lg:inline-flex lg:py-6 lg:px-0 lg:mr-0 lg:ml-8">Portfolio</a>
                  </li>
                  <li class="group">
                    <a href="#clients" class="text-base text-slate-900 py-2 mx-8 flex group-hover:text-teal-500 lg:inline-flex lg:py-6 lg:px-0 lg:mr-0 lg:ml-8">Clients</a>
                  </li>
                  <li class="group">
                    <a href="#blog" class="text-base text-slate-900 py-2 mx-8 flex group-hover:text-teal-500 lg:inline-flex lg:py-6 lg:px-0 lg:mr-0 lg:ml-8">Blog</a>
                  </li>
                  <li class="group">
                    <a href="#contact" class="text-base text-slate-900 py-2 mx-8 flex group-hover:text-teal-500 lg:inline-flex lg:py-6 lg:px-0 lg:mr-0 lg:ml-8">Contact</a>
                  </li>
                </ul>
              </nav>
            </div>
          </div>
        </div>
      </div>
    </header>
    <!-- Header End -->

    <!-- Hero Section Start -->
    <section id="hero" class="relative pt-36 items-center lg:pt-24">
      <div class="container">
        <div class="flex flex-wrap">
          <div class="w-full self-center px-4 lg:w-1/2">
            <h1 class="text-base font-semibold text-teal-500 mb-3 md:text-xl lg:text-xl">
              Halo Semua 👋, saya <span class="block mt-1 font-bold text-slate-900 text-4xl lg:text-5xl">Sandhika Galih</span>
            </h1>

            <h2 class="font-medium text-slate-500 text-lg mb-5 lg:text-2xl">Lecturer & <span class="text-slate-900">Content Creator</span></h2>

            <p class="max-w-lg font-medium text-slate-400 text- leading-relaxed mb-11">
              Belajar web programming itu mudah dan menyenangkan bukan. <span class="text-slate-800 font-semibold">bukan!</span>
            </p>

            <a href="#" class="text-base font-semibold text-white bg-teal-500 py-3 px-8 rounded-full hover:shadow-lg hover:bg-teal-400 transition duration-300 ease-in-out">Hubungi Saya</a>
          </div>

          <div class="w-full self-end px-4 lg:w-1/2">
            <div class="relative mt-12 lg:mt-0 lg:right-0">
              <img src="https://sandhikagalih.github.io/ngobar-tailwind-3/dist/img/hero-profile.png" alt="Sandhika Galih" class="max-w-full mx-auto" />
              <span class="absolute bottom-0 left-1/2 -z-10 -translate-x-1/2 md:scale-125">
                <svg width="400" height="400" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
                  <path
                    fill="#08BDBA"
                    d="M64.1,-21.5C70.9,-0.1,55.7,27.8,33.1,43.8C10.5,59.7,-19.4,63.8,-40.2,49.9C-61,36.1,-72.8,4.3,-64.5,-19.2C-56.3,-42.7,-28.2,-57.9,0.3,-57.9C28.7,-58,57.4,-43,64.1,-21.5Z"
                    transform="translate(100 100) scale(1.3)"
                  />
                </svg>
              </span>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Hero Section End -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#1E293B" fill-opacity="1" d="M0,96L30,96C60,96,120,96,180,128C240,160,300,224,360,250.7C420,277,480,267,540,218.7C600,171,660,85,720,80C780,75,840,149,900,176C960,203,1020,181,1080,154.7C1140,128,1200,96,1260,80C1320,64,1380,64,1410,64L1440,64L1440,320L1410,320C1380,320,1320,320,1260,320C1200,320,1140,320,1080,320C1020,320,960,320,900,320C840,320,780,320,720,320C660,320,600,320,540,320C480,320,420,320,360,320C300,320,240,320,180,320C120,320,60,320,30,320L0,320Z"></path></svg><hr style="height:9px;border:none;color:#1E293B;background-color:#1E293B;" />
    <!-- About Section Start -->
    <section id="about" class="pt-98 pb-3200 relative z-10 bg-slate-800">
      <div class="container">
        <div class="flex flex-wrap">
          <div class="w-full px-4 mb-8 lg:w-1/2">
            <h4 class="font-bold uppercase text-teal-500 text-lg mb-3">Tentang saya</h4>
            <h2 class="max-w-md font-bold text-slate-200 text-3xl mb-5 lg:text-4xl">Yuk, belajar web programming di WPU!</h2>
            <p class="max-w-xl font-medium text-base text-slate-400 lg:text-lg">
              Lorem ipsum dolor sit amet consectetur, adipisicing elit. Fuga aspernatur iure natus debitis reiciendis saepe sit, possimus rerum quibusdam quaerat.
            </p>
          </div>
          <div class="w-full px-4 lg:w-1/2">
            <h3 class="font-semibold text-slate-200 text-2xl mb-4 lg:text-3xl lg:pt-10">Mari berteman</h3>
            <p class="font-medium text-base text-slate-400 mb-6 lg:text-lg">Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam quaerat dolor cupiditate natus animi doloribus ducimus.</p>
            <div class="flex items-center">
              <!-- Youtube -->
              <a href="#" class="w-9 h-9 mr-3 rounded-full flex items-center justify-center border border-slate-300 text-slate-300 hover:bg-teal-500 hover:border-teal-500 hover:text-white">
                <svg role="img" width="20" class="fill-current" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <title>YouTube</title>
                  <path
                    d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12l-6.273 3.568z"
                  />
                </svg>
              </a>

              <!-- Instagram -->
              <a href="#" class="w-9 h-9 mr-3 rounded-full flex items-center justify-center border border-slate-300 text-slate-300 hover:bg-teal-500 hover:border-teal-500 hover:text-white">
                <svg role="img" viewBox="0 0 24 24" width="20" class="fill-current" xmlns="http://www.w3.org/2000/svg">
                  <title>Instagram</title>
                  <path
                    d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913.306.788.717 1.459 1.384 2.126.667.666 1.336 1.079 2.126 1.384.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558.788-.306 1.459-.718 2.126-1.384.666-.667 1.079-1.335 1.384-2.126.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913-.306-.789-.718-1.459-1.384-2.126C21.319 1.347 20.651.935 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227-.224.562-.479.96-.899 1.382-.419.419-.824.679-1.38.896-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421-.569-.224-.96-.479-1.379-.899-.421-.419-.69-.824-.9-1.38-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678c-3.405 0-6.162 2.76-6.162 6.162 0 3.405 2.76 6.162 6.162 6.162 3.405 0 6.162-2.76 6.162-6.162 0-3.405-2.76-6.162-6.162-6.162zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405c0 .795-.646 1.44-1.44 1.44-.795 0-1.44-.646-1.44-1.44 0-.794.646-1.439 1.44-1.439.793-.001 1.44.645 1.44 1.439z"
                  />
                </svg>
              </a>

              <!-- Twitter -->
              <a href="#" class="w-9 h-9 mr-3 rounded-full flex items-center justify-center border border-slate-300 text-slate-300 hover:bg-teal-500 hover:border-teal-500 hover:text-white">
                <svg role="img" viewBox="0 0 24 24" width="20" class="fill-current" xmlns="http://www.w3.org/2000/svg">
                  <title>Twitter</title>
                  <path
                    d="M23.953 4.57a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.69 8.095 4.067 6.13 1.64 3.162a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.06a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.936 4.936 0 004.604 3.417 9.867 9.867 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.053 0 13.998-7.496 13.998-13.985 0-.21 0-.42-.015-.63A9.935 9.935 0 0024 4.59z"
                  />
                </svg>
              </a>

              <!-- Tiktok -->
              <a href="#" class="w-9 h-9 mr-3 rounded-full flex items-center justify-center border border-slate-300 text-slate-300 hover:bg-teal-500 hover:border-teal-500 hover:text-white">
                <svg role="img" viewBox="0 0 24 24" width="20" class="fill-current" xmlns="http://www.w3.org/2000/svg">
                  <title>TikTok</title>
                  <path
                    d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.72 2.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z"
                  />
                </svg>
              </a>

              <!-- LinkedIn -->
              <a href="#" class="w-9 h-9 mr-3 rounded-full flex items-center justify-center border border-slate-300 text-slate-300 hover:bg-teal-500 hover:border-teal-500 hover:text-white">
                <svg role="img" viewBox="0 0 24 24" width="20" class="fill-current" xmlns="http://www.w3.org/2000/svg">
                  <title>LinkedIn</title>
                  <path
                    d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"
                  />
                </svg>
              </a>

              <!-- Discord -->
              <a href="#" class="w-9 h-9 mr-3 rounded-full flex items-center justify-center border border-slate-300 text-slate-300 hover:bg-teal-500 hover:border-teal-500 hover:text-white">
                <svg role="img" viewBox="0 0 24 24" width="20" class="fill-current" xmlns="http://www.w3.org/2000/svg">
                  <title>Discord</title>
                  <path
                    d="M20.317 4.3698a19.7913 19.7913 0 00-4.8851-1.5152.0741.0741 0 00-.0785.0371c-.211.3753-.4447.8648-.6083 1.2495-1.8447-.2762-3.68-.2762-5.4868 0-.1636-.3933-.4058-.8742-.6177-1.2495a.077.077 0 00-.0785-.037 19.7363 19.7363 0 00-4.8852 1.515.0699.0699 0 00-.0321.0277C.5334 9.0458-.319 13.5799.0992 18.0578a.0824.0824 0 00.0312.0561c2.0528 1.5076 4.0413 2.4228 5.9929 3.0294a.0777.0777 0 00.0842-.0276c.4616-.6304.8731-1.2952 1.226-1.9942a.076.076 0 00-.0416-.1057c-.6528-.2476-1.2743-.5495-1.8722-.8923a.077.077 0 01-.0076-.1277c.1258-.0943.2517-.1923.3718-.2914a.0743.0743 0 01.0776-.0105c3.9278 1.7933 8.18 1.7933 12.0614 0a.0739.0739 0 01.0785.0095c.1202.099.246.1981.3728.2924a.077.077 0 01-.0066.1276 12.2986 12.2986 0 01-1.873.8914.0766.0766 0 00-.0407.1067c.3604.698.7719 1.3628 1.225 1.9932a.076.076 0 00.0842.0286c1.961-.6067 3.9495-1.5219 6.0023-3.0294a.077.077 0 00.0313-.0552c.5004-5.177-.8382-9.6739-3.5485-13.6604a.061.061 0 00-.0312-.0286zM8.02 15.3312c-1.1825 0-2.1569-1.0857-2.1569-2.419 0-1.3332.9555-2.4189 2.157-2.4189 1.2108 0 2.1757 1.0952 2.1568 2.419 0 1.3332-.9555 2.4189-2.1569 2.4189zm7.9748 0c-1.1825 0-2.1569-1.0857-2.1569-2.419 0-1.3332.9554-2.4189 2.1569-2.4189 1.2108 0 2.1757 1.0952 2.1568 2.419 0 1.3332-.946 2.4189-2.1568 2.4189Z"
                  />
                </svg>
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#1E293B" fill-opacity="1" d="M0,96L48,122.7C96,149,192,203,288,213.3C384,224,480,192,576,154.7C672,117,768,75,864,85.3C960,96,1056,160,1152,192C1248,224,1344,224,1392,224L1440,224L1440,0L1392,0C1344,0,1248,0,1152,0C1056,0,960,0,864,0C768,0,672,0,576,0C480,0,384,0,288,0C192,0,96,0,48,0L0,0Z"></path></svg>
    <!-- About Section End -->

    <!-- Portfolio Section Start -->
    <section id="portfolio" class="pt-32 pb-16 bg-slate-100">
      <div class="container">
        <div class="w-full px-4">
          <div class="max-w-xl mx-auto text-center mb-16">
            <span class="font-semibold text-lg text-teal-500 block mb-2">Portfolio</span>
            <h2 class="font-bold text-slate-900 text-3xl sm:text-4xl md:text-5xl mb-4">Project Terbaru</h2>
            <p class="font-medium text-md text-slate-500">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime commodi corporis eligendi facere nemo ea doloribus?</p>
          </div>
        </div>

        <div class="flex justify-center">
          <div class="w-full px-4 flex flex-wrap justify-center xl:w-10/12">
            <div class="mb-12 px-4 md:w-1/2">
              <div class="overflow-hidden shadow-sm rounded-md">
                <img src="./dist/img/portfolio/1.png" alt="Landing Page" class="w-full" />
              </div>
              <h3 class="mt-5">
                <a href="#" class="font-semibold text-slate-900 text-xl inline-block mb-3 hover:text-teal-500">Sandhikagalih's landing page</a>
              </h3>
              <p class="font-medium text-base text-slate-500">Lorem ipsum dolor sit amet consectetur adipi elit. Dolore, doloremque. Cum asperiores aspernatur nostrum illum ex.</p>
            </div>
            <div class="mb-12 px-4 md:w-1/2">
              <div class="overflow-hidden shadow-sm rounded-md">
                <img src="./dist/img/portfolio/2.png" alt="Landing Page" class="w-full" />
              </div>
              <h3 class="mt-5">
                <a href="#" class="font-semibold text-slate-900 text-xl inline-block mb-3 hover:text-teal-500">CSS Grid</a>
              </h3>
              <p class="font-medium text-base text-slate-500">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ullam pariatur impedit repellendus perspiciatis voluptatem.</p>
            </div>
            <div class="mb-12 px-4 md:w-1/2">
              <div class="overflow-hidden shadow-sm rounded-md">
                <img src="./dist/img/portfolio/3.png" alt="Technical Documentation" class="w-full" />
              </div>
              <h3 class="mt-5">
                <a href="#" class="font-semibold text-slate-900 text-xl inline-block mb-3 hover:text-teal-500">Technical Documentation</a>
              </h3>
              <p class="font-medium text-base text-slate-500">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci, maxime fuga. Voluptatem tenetur neque enim nulla illum eos itaque maxime?
              </p>
            </div>
            <div class="mb-12 px-4 md:w-1/2">
              <div class="overflow-hidden shadow-sm rounded-md">
                <img src="./dist/img/portfolio/4.png" alt="Tribute Page" class="w-full" />
              </div>
              <h3 class="mt-5">
                <a href="#" class="font-semibold text-slate-900 text-xl inline-block mb-3 hover:text-teal-500">Tribute Page</a>
              </h3>
              <p class="font-medium text-base text-slate-500">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis nobis beatae commodi, numquam fugiat facere amet, aliquam, tempore rem quasi nesciunt similique!
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Portfolio Section End -->

    <!-- Clients Section Start -->
    <section id="clients" class="pt-20 pb-28 bg-slate-800 relative">
      <div class="container">
        <div class="w-full px-4">
          <div class="max-w-2xl mx-auto mb-12 text-center">
            <span class="font-semibold text-lg text-teal-500 block mb-2">Client</span>
            <h2 class="font-bold text-3xl sm:text-4xl md:text-5xl text-white mb-4">Yang Pernah Bekerjasama</h2>
            <p class="font-medium text-md md:text-lg text-slate-600">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum id numquam molestiae voluptatibus eius.</p>
          </div>
        </div>

        <div class="w-full px-4">
          <div class="flex flex-wrap items-center justify-center">
            <a href="#" class="max-w-[120px] mx-4 py-4 grayscale opacity-60 transition hover:opacity-100 hover:grayscale-0 lg:mx-6 xl:mx-8">
              <img src="https://raw.githubusercontent.com/fardanadhim/logoh/master/html-cui.svg" alt="Google" />
            </a>
            <a href="#" class="max-w-[120px] mx-4 py-4 grayscale opacity-60 transition hover:opacity-100 hover:grayscale-0 lg:mx-6 xl:mx-8">
              <img src="https://raw.githubusercontent.com/fardanadhim/logoh/master/css-3-cui.svg" alt="Gojek" />
            </a>
            <a href="#" class="max-w-[100px] mx-4 py-4 grayscale opacity-60 transition hover:opacity-100 hover:grayscale-0 lg:mx-6 xl:mx-8">
              <img src="https://raw.githubusercontent.com/fardanadhim/logoh/master/js-logo.svg" alt="Traveloka" />
            </a>
            <a href="#" class="max-w-[120px] mx-4 py-4 grayscale opacity-60 transition hover:opacity-100 hover:grayscale-0 lg:mx-6 xl:">
              <img src="https://raw.githubusercontent.com/fardanadhim/logoh/master/tailwind-logoh.svg" alt="Tokopedia" />
            </a>
          </div>
        </div>
      </div>
    </section>
    <!-- Clients Section End -->

    <!-- Blog Section Start -->
    <section id="blog" class="py-20 bg-slate-100">
      <div class="container">
        <div class="w-full px-4">
          <div class="max-w-2xl mx-auto mb-12 text-center">
            <span class="font-semibold text-lg text-teal-500 block mb-2">Blog</span>
            <h2 class="font-bold text-3xl sm:text-4xl md:text-5xl text-slate-900 mb-4">Tulisan Terkini</h2>
            <p class="font-medium text-md md:text-lg text-slate-500">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nostrum quam modi labore quae quod!</p>
          </div>
        </div>

        <div class="flex flex-wrap">
          <div class="w-full px-4 lg:w-1/2 xl:w-1/3">
            <div class="bg-white rounded-xl overflow-hidden mb-10 shadow-lg">
              <a href="#" class="block">
                <img src="https://source.unsplash.com/360x200?programming" alt="Programming" class="w-full" />
              </a>
              <div class="py-8 px-6">
                <h3>
                  <a href="#" class="block mb-3 font-semibold text-xl text-slate-900 hover:text-teal-500 truncate"> Tips Belajar Programming </a>
                </h3>
                <p class="font-medium text-slate-500 text-base mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores hic quae iste labore! Accusantium, distinctio!</p>
                <a href="#" class="font-medium text-sm text-slate-900 underline hover:text-teal-500 hover:no-underline">Baca Selangkapnya</a>
              </div>
            </div>
          </div>

          <div class="w-full px-4 lg:w-1/2 xl:w-1/3">
            <div class="bg-white rounded-xl overflow-hidden mb-10 shadow-lg">
              <a href="#" class="block">
                <img src="https://source.unsplash.com/360x200?mechanical+keyboard" alt="Keyboard" class="w-full" />
              </a>
              <div class="py-8 px-6">
                <h3>
                  <a href="#" class="block mb-3 font-semibold text-xl text-slate-900 hover:text-teal-500 truncate">Review Keyboard GMMK Pro</a>
                </h3>
                <p class="font-medium text-slate-500 text-base mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit, est nostrum. Sequi, illum asperiores.</p>
                <a href="#" class="font-medium text-sm text-slate-900 underline hover:text-teal-500 hover:no-underline">Baca Selangkapnya</a>
              </div>
            </div>
          </div>

          <div class="w-full px-4 lg:w-1/2 xl:w-1/3">
            <div class="bg-white rounded-xl overflow-hidden mb-10 shadow-lg">
              <a href="#" class="block">
                <img src="https://source.unsplash.com/360x200?coffee" alt="Kopi" class="w-full" />
              </a>
              <div class="py-8 px-6">
                <h3>
                  <a href="#" class="block mb-3 font-semibold text-xl text-slate-900 hover:text-teal-500 truncate">Menikmati Secangkir Kopi</a>
                </h3>
                <p class="font-medium text-slate-500 text-base mb-4">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Consequatur aliquam ullam molestiae fugiat quod optio odio.</p>
                <a href="#" class="font-medium text-sm text-slate-900 underline hover:text-teal-500 hover:no-underline">Baca Selangkapnya</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Blog Section End -->

    <!-- Contact Section Start -->
    <section id="contact" class="py-20">
      <div class="container">
        <div class="w-full px-4">
          <div class="max-w-xl mx-auto text-center mb-12">
            <span class="font-semibold text-lg text-teal-500 block mb-2">Contact</span>
            <h2 class="font-bold text-slate-900 text-3xl sm:text-4xl md:text-5xl mb-4">Hubungi Kami</h2>
            <p class="font-medium text-md text-slate-500">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Perspiciatis eligendi eos rerum nisi consequuntur impedit hic?</p>
          </div>
        </div>

        <div class="w-full px-4 flex flex-wrap justify-center">
          <div class="w-full lg:w-2/3">
            <div class="w-full mb-8">
              <label for="name" class="text-base text-teal-500 font-semibold">Nama</label>
              <input type="text" id="name" class="w-full bg-slate-200 text-slate-900 p-3 rounded-md focus:outline-none" />
            </div>
            <div class="w-full mb-8">
              <label for="email" class="text-base text-teal-500 font-semibold">Email</label>
              <input type="email" id="email" class="w-full bg-slate-200 text-slate-900 p-3 rounded-md focus:outline-none" />
            </div>
            <div class="w-full mb-8">
              <label for="message" class="text-base text-teal-500 font-semibold">Pesan</label>
              <textarea id="message" class="w-full bg-slate-200 text-slate-900 p-3 rounded-md focus:outline-none h-32"></textarea>
            </div>
            <div class="w-full mb-8 lg:w-1/3 mx-auto">
              <button class="text-base font-semibold text-white bg-teal-500 py-3 px-8 rounded-full hover:shadow-lg hover:bg-teal-400 transition duration-300 ease-in-out w-full">Kirim</button>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Contact Section End -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#0F172A" fill-opacity="1" d="M0,0L40,48C80,96,160,192,240,197.3C320,203,400,117,480,85.3C560,53,640,75,720,112C800,149,880,203,960,240C1040,277,1120,299,1200,256C1280,213,1360,107,1400,53.3L1440,0L1440,320L1400,320C1360,320,1280,320,1200,320C1120,320,1040,320,960,320C880,320,800,320,720,320C640,320,560,320,480,320C400,320,320,320,240,320C160,320,80,320,40,320L0,320Z"></path></svg>
    <!-- Footer Section Start -->
    <footer class="bg-slate-900 pt-24 pb-12">
      <div class="container">
        <div class="flex flex-wrap">
          <div class="w-full px-4 mb-14 md:w-1/3">
            <div class="mb-10">
              <h2 class="font-bold text-white text-4xl leading-tight mb-5">WPU</h2>
              <h3 class="font-bold text-slate-400 text-2xl mb-1">Hubungi Kami</h3>
              <p class="font-medium text-base text-slate-400">sandhikagalih@gmail.com</p>
              <p class="font-medium text-base text-slate-400">Jl. Dr. Setiabudhi No. 193</p>
              <p class="font-medium text-base text-slate-400">Bandung</p>
            </div>
          </div>

          <div class="w-full px-4 mb-14 md:w-1/3">
            <div class="mb-10">
              <h3 class="font-semibold text-white text-xl mb-5">Kategori Tulisan</h3>
              <ul>
                <li>
                  <a href="#" class="inline-block text-base text-slate-400 mb-3">Programming</a>
                </li>
                <li>
                  <a href="#" class="inline-block text-base text-slate-400 mb-3">Teknologi</a>
                </li>
                <li>
                  <a href="#" class="inline-block text-base text-slate-400 mb-3">Gaya Hidup</a>
                </li>
              </ul>
            </div>
          </div>

          <div class="w-full px-4 mb-14 md:w-1/3">
            <div class="mb-10">
              <h3 class="font-semibold text-white text-xl mb-5">Tautan</h3>
              <ul>
                <li>
                  <a href="#" class="inline-block text-base text-slate-400 mb-3">Beranda</a>
                </li>
                <li>
                  <a href="#" class="inline-block text-base text-slate-400 mb-3">Tentang Saya</a>
                </li>
                <li>
                  <a href="#" class="inline-block text-base text-slate-400 mb-3">Portfolio</a>
                </li>
                <li>
                  <a href="#" class="inline-block text-base text-slate-400 mb-3">Clients</a>
                </li>
                <li>
                  <a href="#" class="inline-block text-base text-slate-400 mb-3">Blog</a>
                </li>
                <li>
                  <a href="#" class="inline-block text-base text-slate-400 mb-3">Contact</a>
                </li>
              </ul>
            </div>
          </div>
        </div>

        <div class="pt-10 border-t border-slate-800">
          <div class="flex items-center justify-center mb-5">
            <!-- Youtube -->
            <a href="#" class="w-9 h-9 mr-3 rounded-full flex items-center justify-center border border-slate-300 text-slate-300 hover:bg-teal-500 hover:border-teal-500 hover:text-white">
              <svg role="img" width="20" class="fill-current" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <title>YouTube</title>
                <path
                  d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12l-6.273 3.568z"
                />
              </svg>
            </a>

            <!-- Instagram -->
            <a href="#" class="w-9 h-9 mr-3 rounded-full flex items-center justify-center border border-slate-300 text-slate-300 hover:bg-teal-500 hover:border-teal-500 hover:text-white">
              <svg role="img" viewBox="0 0 24 24" width="20" class="fill-current" xmlns="http://www.w3.org/2000/svg">
                <title>Instagram</title>
                <path
                  d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913.306.788.717 1.459 1.384 2.126.667.666 1.336 1.079 2.126 1.384.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558.788-.306 1.459-.718 2.126-1.384.666-.667 1.079-1.335 1.384-2.126.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913-.306-.789-.718-1.459-1.384-2.126C21.319 1.347 20.651.935 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227-.224.562-.479.96-.899 1.382-.419.419-.824.679-1.38.896-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421-.569-.224-.96-.479-1.379-.899-.421-.419-.69-.824-.9-1.38-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678c-3.405 0-6.162 2.76-6.162 6.162 0 3.405 2.76 6.162 6.162 6.162 3.405 0 6.162-2.76 6.162-6.162 0-3.405-2.76-6.162-6.162-6.162zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405c0 .795-.646 1.44-1.44 1.44-.795 0-1.44-.646-1.44-1.44 0-.794.646-1.439 1.44-1.439.793-.001 1.44.645 1.44 1.439z"
                />
              </svg>
            </a>

            <!-- Twitter -->
            <a href="#" class="w-9 h-9 mr-3 rounded-full flex items-center justify-center border border-slate-300 text-slate-300 hover:bg-teal-500 hover:border-teal-500 hover:text-white">
              <svg role="img" viewBox="0 0 24 24" width="20" class="fill-current" xmlns="http://www.w3.org/2000/svg">
                <title>Twitter</title>
                <path
                  d="M23.953 4.57a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.69 8.095 4.067 6.13 1.64 3.162a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.06a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.936 4.936 0 004.604 3.417 9.867 9.867 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.053 0 13.998-7.496 13.998-13.985 0-.21 0-.42-.015-.63A9.935 9.935 0 0024 4.59z"
                />
              </svg>
            </a>

            <!-- Tiktok -->
            <a href="#" class="w-9 h-9 mr-3 rounded-full flex items-center justify-center border border-slate-300 text-slate-300 hover:bg-teal-500 hover:border-teal-500 hover:text-white">
              <svg role="img" viewBox="0 0 24 24" width="20" class="fill-current" xmlns="http://www.w3.org/2000/svg">
                <title>TikTok</title>
                <path
                  d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.72 2.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z"
                />
              </svg>
            </a>

            <!-- LinkedIn -->
            <a href="#" class="w-9 h-9 mr-3 rounded-full flex items-center justify-center border border-slate-300 text-slate-300 hover:bg-teal-500 hover:border-teal-500 hover:text-white">
              <svg role="img" viewBox="0 0 24 24" width="20" class="fill-current" xmlns="http://www.w3.org/2000/svg">
                <title>LinkedIn</title>
                <path
                  d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"
                />
              </svg>
            </a>

            <!-- Discord -->
            <a href="#" class="w-9 h-9 mr-3 rounded-full flex items-center justify-center border border-slate-300 text-slate-300 hover:bg-teal-500 hover:border-teal-500 hover:text-white">
              <svg role="img" viewBox="0 0 24 24" width="20" class="fill-current" xmlns="http://www.w3.org/2000/svg">
                <title>Discord</title>
                <path
                  d="M20.317 4.3698a19.7913 19.7913 0 00-4.8851-1.5152.0741.0741 0 00-.0785.0371c-.211.3753-.4447.8648-.6083 1.2495-1.8447-.2762-3.68-.2762-5.4868 0-.1636-.3933-.4058-.8742-.6177-1.2495a.077.077 0 00-.0785-.037 19.7363 19.7363 0 00-4.8852 1.515.0699.0699 0 00-.0321.0277C.5334 9.0458-.319 13.5799.0992 18.0578a.0824.0824 0 00.0312.0561c2.0528 1.5076 4.0413 2.4228 5.9929 3.0294a.0777.0777 0 00.0842-.0276c.4616-.6304.8731-1.2952 1.226-1.9942a.076.076 0 00-.0416-.1057c-.6528-.2476-1.2743-.5495-1.8722-.8923a.077.077 0 01-.0076-.1277c.1258-.0943.2517-.1923.3718-.2914a.0743.0743 0 01.0776-.0105c3.9278 1.7933 8.18 1.7933 12.0614 0a.0739.0739 0 01.0785.0095c.1202.099.246.1981.3728.2924a.077.077 0 01-.0066.1276 12.2986 12.2986 0 01-1.873.8914.0766.0766 0 00-.0407.1067c.3604.698.7719 1.3628 1.225 1.9932a.076.076 0 00.0842.0286c1.961-.6067 3.9495-1.5219 6.0023-3.0294a.077.077 0 00.0313-.0552c.5004-5.177-.8382-9.6739-3.5485-13.6604a.061.061 0 00-.0312-.0286zM8.02 15.3312c-1.1825 0-2.1569-1.0857-2.1569-2.419 0-1.3332.9555-2.4189 2.157-2.4189 1.2108 0 2.1757 1.0952 2.1568 2.419 0 1.3332-.9555 2.4189-2.1569 2.4189zm7.9748 0c-1.1825 0-2.1569-1.0857-2.1569-2.419 0-1.3332.9554-2.4189 2.1569-2.4189 1.2108 0 2.1757 1.0952 2.1568 2.419 0 1.3332-.946 2.4189-2.1568 2.4189Z"
                />
              </svg>
            </a>
          </div>
          <p class="font-medium text-sm text-slate-500 text-center">
            Dibuat dengan <span class="text-pink-500">❤️</span> oleh <a href="http://instagram.com/sandhikagalih" class="font-bold text-teal-500">Sandhika Galih</a>, menggunakan
            <a href="https://tailwindcss.com/" class="font-bold text-sky-500">Tailwind CSS 3</a>.
          </p>
        </div>
      </div>
    </footer>
    <!-- Footer Section End -->

    <script src="https://sandhikagalih.github.io/ngobar-tailwind-3/dist/js/script.js"></script>
  </body>
</html>


