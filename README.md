<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>React Artifact</title>
  <style>@import url("https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&family=Sora:wght@700;800&display=swap");
*, ::before, ::after{
  --tw-border-spacing-x: 0;
  --tw-border-spacing-y: 0;
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
  --tw-gradient-from-position:  ;
  --tw-gradient-via-position:  ;
  --tw-gradient-to-position:  ;
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
  --tw-contain-size:  ;
  --tw-contain-layout:  ;
  --tw-contain-paint:  ;
  --tw-contain-style:  ;
}
::backdrop{
  --tw-border-spacing-x: 0;
  --tw-border-spacing-y: 0;
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
  --tw-gradient-from-position:  ;
  --tw-gradient-via-position:  ;
  --tw-gradient-to-position:  ;
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
  --tw-contain-size:  ;
  --tw-contain-layout:  ;
  --tw-contain-paint:  ;
  --tw-contain-style:  ;
}
/*
! tailwindcss v3.4.18 | MIT License | https://tailwindcss.com
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
5. Use the user's configured `sans` font-feature-settings by default.
6. Use the user's configured `sans` font-variation-settings by default.
7. Disable tap highlights on iOS
*/
html,
:host {
  line-height: 1.5;
  /* 1 */
  -webkit-text-size-adjust: 100%;
  /* 2 */
  -moz-tab-size: 4;
  /* 3 */
  -o-tab-size: 4;
     tab-size: 4;
  /* 3 */
  font-family: ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  /* 4 */
  font-feature-settings: normal;
  /* 5 */
  font-variation-settings: normal;
  /* 6 */
  -webkit-tap-highlight-color: transparent;
  /* 7 */
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
1. Use the user's configured `mono` font-family by default.
2. Use the user's configured `mono` font-feature-settings by default.
3. Use the user's configured `mono` font-variation-settings by default.
4. Correct the odd `em` font sizing in all browsers.
*/
code,
kbd,
samp,
pre {
  font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
  /* 1 */
  font-feature-settings: normal;
  /* 2 */
  font-variation-settings: normal;
  /* 3 */
  font-size: 1em;
  /* 4 */
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
  font-feature-settings: inherit;
  /* 1 */
  font-variation-settings: inherit;
  /* 1 */
  font-size: 100%;
  /* 1 */
  font-weight: inherit;
  /* 1 */
  line-height: inherit;
  /* 1 */
  letter-spacing: inherit;
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
input:where([type='button']),
input:where([type='reset']),
input:where([type='submit']) {
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
Reset default styling for dialogs.
*/
dialog {
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
/* Make elements with the HTML hidden attribute stay hidden by default */
[hidden]:where(:not([hidden="until-found"])) {
  display: none;
}
.fixed{
  position: fixed;
}
.absolute{
  position: absolute;
}
.relative{
  position: relative;
}
.sticky{
  position: sticky;
}
.inset-0{
  inset: 0px;
}
.-right-8{
  right: -2rem;
}
.-top-8{
  top: -2rem;
}
.bottom-5{
  bottom: 1.25rem;
}
.left-1\/2{
  left: 50%;
}
.top-\[var\(--safe-area-inset-top\)\]{
  top: var(--safe-area-inset-top);
}
.z-40{
  z-index: 40;
}
.z-50{
  z-index: 50;
}
.z-\[60\]{
  z-index: 60;
}
.-mx-1{
  margin-left: -0.25rem;
  margin-right: -0.25rem;
}
.mx-auto{
  margin-left: auto;
  margin-right: auto;
}
.mb-2{
  margin-bottom: 0.5rem;
}
.mb-3{
  margin-bottom: 0.75rem;
}
.mb-4{
  margin-bottom: 1rem;
}
.mb-6{
  margin-bottom: 1.5rem;
}
.mb-8{
  margin-bottom: 2rem;
}
.ml-auto{
  margin-left: auto;
}
.mt-0\.5{
  margin-top: 0.125rem;
}
.mt-1{
  margin-top: 0.25rem;
}
.mt-10{
  margin-top: 2.5rem;
}
.mt-2{
  margin-top: 0.5rem;
}
.mt-3{
  margin-top: 0.75rem;
}
.mt-4{
  margin-top: 1rem;
}
.mt-5{
  margin-top: 1.25rem;
}
.mt-6{
  margin-top: 1.5rem;
}
.mt-7{
  margin-top: 1.75rem;
}
.mt-8{
  margin-top: 2rem;
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
.inline-flex{
  display: inline-flex;
}
.grid{
  display: grid;
}
.hidden{
  display: none;
}
.h-10{
  height: 2.5rem;
}
.h-11{
  height: 2.75rem;
}
.h-12{
  height: 3rem;
}
.h-2{
  height: 0.5rem;
}
.h-20{
  height: 5rem;
}
.h-4{
  height: 1rem;
}
.h-40{
  height: 10rem;
}
.h-6{
  height: 1.5rem;
}
.h-\[210px\]{
  height: 210px;
}
.h-fit{
  height: -moz-fit-content;
  height: fit-content;
}
.h-full{
  height: 100%;
}
.max-h-\[260px\]{
  max-height: 260px;
}
.max-h-\[92vh\]{
  max-height: 92vh;
}
.min-h-screen{
  min-height: 100vh;
}
.w-10{
  width: 2.5rem;
}
.w-11{
  width: 2.75rem;
}
.w-12{
  width: 3rem;
}
.w-2{
  width: 0.5rem;
}
.w-20{
  width: 5rem;
}
.w-40{
  width: 10rem;
}
.w-6{
  width: 1.5rem;
}
.w-8{
  width: 2rem;
}
.w-\[210px\]{
  width: 210px;
}
.w-full{
  width: 100%;
}
.min-w-0{
  min-width: 0px;
}
.min-w-\[200px\]{
  min-width: 200px;
}
.min-w-\[260px\]{
  min-width: 260px;
}
.max-w-2xl{
  max-width: 42rem;
}
.max-w-\[1440px\]{
  max-width: 1440px;
}
.max-w-\[560px\]{
  max-width: 560px;
}
.max-w-\[640px\]{
  max-width: 640px;
}
.max-w-\[760px\]{
  max-width: 760px;
}
.max-w-\[92vw\]{
  max-width: 92vw;
}
.max-w-xl{
  max-width: 36rem;
}
.flex-1{
  flex: 1 1 0%;
}
.shrink-0{
  flex-shrink: 0;
}
.-translate-x-1\/2{
  --tw-translate-x: -50%;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}
.scale-\[1\.02\]{
  --tw-scale-x: 1.02;
  --tw-scale-y: 1.02;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}
.transform{
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}
@keyframes pulse{
  50%{
    opacity: .5;
  }
}
.animate-pulse{
  animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
}
.cursor-pointer{
  cursor: pointer;
}
.grid-cols-2{
  grid-template-columns: repeat(2, minmax(0, 1fr));
}
.flex-wrap{
  flex-wrap: wrap;
}
.place-items-center{
  place-items: center;
}
.items-start{
  align-items: flex-start;
}
.items-end{
  align-items: flex-end;
}
.items-center{
  align-items: center;
}
.justify-between{
  justify-content: space-between;
}
.gap-1{
  gap: 0.25rem;
}
.gap-1\.5{
  gap: 0.375rem;
}
.gap-2{
  gap: 0.5rem;
}
.gap-3{
  gap: 0.75rem;
}
.gap-4{
  gap: 1rem;
}
.gap-5{
  gap: 1.25rem;
}
.gap-6{
  gap: 1.5rem;
}
.gap-8{
  gap: 2rem;
}
.space-y-6 > :not([hidden]) ~ :not([hidden]){
  --tw-space-y-reverse: 0;
  margin-top: calc(1.5rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(1.5rem * var(--tw-space-y-reverse));
}
.space-y-8 > :not([hidden]) ~ :not([hidden]){
  --tw-space-y-reverse: 0;
  margin-top: calc(2rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(2rem * var(--tw-space-y-reverse));
}
.divide-y > :not([hidden]) ~ :not([hidden]){
  --tw-divide-y-reverse: 0;
  border-top-width: calc(1px * calc(1 - var(--tw-divide-y-reverse)));
  border-bottom-width: calc(1px * var(--tw-divide-y-reverse));
}
.divide-slate-100 > :not([hidden]) ~ :not([hidden]){
  --tw-divide-opacity: 1;
  border-color: rgb(241 245 249 / var(--tw-divide-opacity, 1));
}
.overflow-hidden{
  overflow: hidden;
}
.overflow-x-auto{
  overflow-x: auto;
}
.overflow-y-auto{
  overflow-y: auto;
}
.truncate{
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}
.rounded-2xl{
  border-radius: 1rem;
}
.rounded-\[20px\]{
  border-radius: 20px;
}
.rounded-\[24px\]{
  border-radius: 24px;
}
.rounded-\[28px\]{
  border-radius: 28px;
}
.rounded-full{
  border-radius: 9999px;
}
.rounded-xl{
  border-radius: 0.75rem;
}
.border{
  border-width: 1px;
}
.border-2{
  border-width: 2px;
}
.border-4{
  border-width: 4px;
}
.border-\[3px\]{
  border-width: 3px;
}
.border-\[6px\]{
  border-width: 6px;
}
.border-b-2{
  border-bottom-width: 2px;
}
.border-t{
  border-top-width: 1px;
}
.border-\[\#F59E0B\]{
  --tw-border-opacity: 1;
  border-color: rgb(245 158 11 / var(--tw-border-opacity, 1));
}
.border-amber-200{
  --tw-border-opacity: 1;
  border-color: rgb(253 230 138 / var(--tw-border-opacity, 1));
}
.border-amber-300{
  --tw-border-opacity: 1;
  border-color: rgb(252 211 77 / var(--tw-border-opacity, 1));
}
.border-amber-400{
  --tw-border-opacity: 1;
  border-color: rgb(251 191 36 / var(--tw-border-opacity, 1));
}
.border-emerald-200{
  --tw-border-opacity: 1;
  border-color: rgb(167 243 208 / var(--tw-border-opacity, 1));
}
.border-emerald-400\/30{
  border-color: rgb(52 211 153 / 0.3);
}
.border-emerald-600{
  --tw-border-opacity: 1;
  border-color: rgb(5 150 105 / var(--tw-border-opacity, 1));
}
.border-red-200{
  --tw-border-opacity: 1;
  border-color: rgb(254 202 202 / var(--tw-border-opacity, 1));
}
.border-red-500{
  --tw-border-opacity: 1;
  border-color: rgb(239 68 68 / var(--tw-border-opacity, 1));
}
.border-slate-100{
  --tw-border-opacity: 1;
  border-color: rgb(241 245 249 / var(--tw-border-opacity, 1));
}
.border-slate-200{
  --tw-border-opacity: 1;
  border-color: rgb(226 232 240 / var(--tw-border-opacity, 1));
}
.border-slate-300{
  --tw-border-opacity: 1;
  border-color: rgb(203 213 225 / var(--tw-border-opacity, 1));
}
.border-white\/10{
  border-color: rgb(255 255 255 / 0.1);
}
.bg-\[\#0F172A\]{
  --tw-bg-opacity: 1;
  background-color: rgb(15 23 42 / var(--tw-bg-opacity, 1));
}
.bg-\[\#0F766E\]{
  --tw-bg-opacity: 1;
  background-color: rgb(15 118 110 / var(--tw-bg-opacity, 1));
}
.bg-\[\#14B8A6\]\/30{
  background-color: rgb(20 184 166 / 0.3);
}
.bg-\[\#F1F5F9\]{
  --tw-bg-opacity: 1;
  background-color: rgb(241 245 249 / var(--tw-bg-opacity, 1));
}
.bg-\[\#F59E0B\]{
  --tw-bg-opacity: 1;
  background-color: rgb(245 158 11 / var(--tw-bg-opacity, 1));
}
.bg-\[\#F8FAFC\]{
  --tw-bg-opacity: 1;
  background-color: rgb(248 250 252 / var(--tw-bg-opacity, 1));
}
.bg-\[var\(--bg\)\]{
  background-color: var(--bg);
}
.bg-amber-100{
  --tw-bg-opacity: 1;
  background-color: rgb(254 243 199 / var(--tw-bg-opacity, 1));
}
.bg-amber-400{
  --tw-bg-opacity: 1;
  background-color: rgb(251 191 36 / var(--tw-bg-opacity, 1));
}
.bg-amber-400\/20{
  background-color: rgb(251 191 36 / 0.2);
}
.bg-amber-50{
  --tw-bg-opacity: 1;
  background-color: rgb(255 251 235 / var(--tw-bg-opacity, 1));
}
.bg-black\/60{
  background-color: rgb(0 0 0 / 0.6);
}
.bg-emerald-100{
  --tw-bg-opacity: 1;
  background-color: rgb(209 250 229 / var(--tw-bg-opacity, 1));
}
.bg-emerald-50{
  --tw-bg-opacity: 1;
  background-color: rgb(236 253 245 / var(--tw-bg-opacity, 1));
}
.bg-emerald-500{
  --tw-bg-opacity: 1;
  background-color: rgb(16 185 129 / var(--tw-bg-opacity, 1));
}
.bg-emerald-500\/20{
  background-color: rgb(16 185 129 / 0.2);
}
.bg-emerald-600{
  --tw-bg-opacity: 1;
  background-color: rgb(5 150 105 / var(--tw-bg-opacity, 1));
}
.bg-red-100{
  --tw-bg-opacity: 1;
  background-color: rgb(254 226 226 / var(--tw-bg-opacity, 1));
}
.bg-red-50{
  --tw-bg-opacity: 1;
  background-color: rgb(254 242 242 / var(--tw-bg-opacity, 1));
}
.bg-red-500{
  --tw-bg-opacity: 1;
  background-color: rgb(239 68 68 / var(--tw-bg-opacity, 1));
}
.bg-slate-100{
  --tw-bg-opacity: 1;
  background-color: rgb(241 245 249 / var(--tw-bg-opacity, 1));
}
.bg-slate-200{
  --tw-bg-opacity: 1;
  background-color: rgb(226 232 240 / var(--tw-bg-opacity, 1));
}
.bg-slate-50{
  --tw-bg-opacity: 1;
  background-color: rgb(248 250 252 / var(--tw-bg-opacity, 1));
}
.bg-slate-800{
  --tw-bg-opacity: 1;
  background-color: rgb(30 41 59 / var(--tw-bg-opacity, 1));
}
.bg-slate-900{
  --tw-bg-opacity: 1;
  background-color: rgb(15 23 42 / var(--tw-bg-opacity, 1));
}
.bg-teal-50{
  --tw-bg-opacity: 1;
  background-color: rgb(240 253 250 / var(--tw-bg-opacity, 1));
}
.bg-white{
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity, 1));
}
.bg-white\/10{
  background-color: rgb(255 255 255 / 0.1);
}
.bg-white\/20{
  background-color: rgb(255 255 255 / 0.2);
}
.bg-white\/80{
  background-color: rgb(255 255 255 / 0.8);
}
.bg-gradient-to-br{
  background-image: linear-gradient(to bottom right, var(--tw-gradient-stops));
}
.bg-gradient-to-r{
  background-image: linear-gradient(to right, var(--tw-gradient-stops));
}
.from-\[\#0F172A\]{
  --tw-gradient-from: #0F172A var(--tw-gradient-from-position);
  --tw-gradient-to: rgb(15 23 42 / 0) var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to);
}
.from-\[\#0F766E\]{
  --tw-gradient-from: #0F766E var(--tw-gradient-from-position);
  --tw-gradient-to: rgb(15 118 110 / 0) var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to);
}
.via-\[\#0F766E\]{
  --tw-gradient-to: rgb(15 118 110 / 0)  var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), #0F766E var(--tw-gradient-via-position), var(--tw-gradient-to);
}
.to-\[\#0F766E\]{
  --tw-gradient-to: #0F766E var(--tw-gradient-to-position);
}
.to-\[\#14B8A6\]{
  --tw-gradient-to: #14B8A6 var(--tw-gradient-to-position);
}
.object-cover{
  -o-object-fit: cover;
     object-fit: cover;
}
.p-1{
  padding: 0.25rem;
}
.p-2{
  padding: 0.5rem;
}
.p-4{
  padding: 1rem;
}
.p-5{
  padding: 1.25rem;
}
.p-6{
  padding: 1.5rem;
}
.p-7{
  padding: 1.75rem;
}
.p-8{
  padding: 2rem;
}
.px-1{
  padding-left: 0.25rem;
  padding-right: 0.25rem;
}
.px-10{
  padding-left: 2.5rem;
  padding-right: 2.5rem;
}
.px-2{
  padding-left: 0.5rem;
  padding-right: 0.5rem;
}
.px-2\.5{
  padding-left: 0.625rem;
  padding-right: 0.625rem;
}
.px-3{
  padding-left: 0.75rem;
  padding-right: 0.75rem;
}
.px-4{
  padding-left: 1rem;
  padding-right: 1rem;
}
.px-5{
  padding-left: 1.25rem;
  padding-right: 1.25rem;
}
.px-6{
  padding-left: 1.5rem;
  padding-right: 1.5rem;
}
.px-7{
  padding-left: 1.75rem;
  padding-right: 1.75rem;
}
.py-0\.5{
  padding-top: 0.125rem;
  padding-bottom: 0.125rem;
}
.py-1{
  padding-top: 0.25rem;
  padding-bottom: 0.25rem;
}
.py-1\.5{
  padding-top: 0.375rem;
  padding-bottom: 0.375rem;
}
.py-2{
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
}
.py-2\.5{
  padding-top: 0.625rem;
  padding-bottom: 0.625rem;
}
.py-3{
  padding-top: 0.75rem;
  padding-bottom: 0.75rem;
}
.py-3\.5{
  padding-top: 0.875rem;
  padding-bottom: 0.875rem;
}
.py-4{
  padding-top: 1rem;
  padding-bottom: 1rem;
}
.py-5{
  padding-top: 1.25rem;
  padding-bottom: 1.25rem;
}
.py-6{
  padding-top: 1.5rem;
  padding-bottom: 1.5rem;
}
.pb-2{
  padding-bottom: 0.5rem;
}
.pb-4{
  padding-bottom: 1rem;
}
.pt-6{
  padding-top: 1.5rem;
}
.text-left{
  text-align: left;
}
.text-center{
  text-align: center;
}
.text-right{
  text-align: right;
}
.text-2xl{
  font-size: 1.5rem;
  line-height: 2rem;
}
.text-3xl{
  font-size: 1.875rem;
  line-height: 2.25rem;
}
.text-4xl{
  font-size: 2.25rem;
  line-height: 2.5rem;
}
.text-5xl{
  font-size: 3rem;
  line-height: 1;
}
.text-6xl{
  font-size: 3.75rem;
  line-height: 1;
}
.text-\[11px\]{
  font-size: 11px;
}
.text-\[12px\]{
  font-size: 12px;
}
.text-\[15px\]{
  font-size: 15px;
}
.text-\[17px\]{
  font-size: 17px;
}
.text-\[19px\]{
  font-size: 19px;
}
.text-base{
  font-size: 1rem;
  line-height: 1.5rem;
}
.text-lg{
  font-size: 1.125rem;
  line-height: 1.75rem;
}
.text-sm{
  font-size: 0.875rem;
  line-height: 1.25rem;
}
.text-xl{
  font-size: 1.25rem;
  line-height: 1.75rem;
}
.text-xs{
  font-size: 0.75rem;
  line-height: 1rem;
}
.font-black{
  font-weight: 900;
}
.font-bold{
  font-weight: 700;
}
.font-extrabold{
  font-weight: 800;
}
.font-medium{
  font-weight: 500;
}
.font-semibold{
  font-weight: 600;
}
.uppercase{
  text-transform: uppercase;
}
.capitalize{
  text-transform: capitalize;
}
.tabular-nums{
  --tw-numeric-spacing: tabular-nums;
  font-variant-numeric: var(--tw-ordinal) var(--tw-slashed-zero) var(--tw-numeric-figure) var(--tw-numeric-spacing) var(--tw-numeric-fraction);
}
.leading-none{
  line-height: 1;
}
.leading-relaxed{
  line-height: 1.625;
}
.leading-snug{
  line-height: 1.375;
}
.leading-tight{
  line-height: 1.25;
}
.tracking-tight{
  letter-spacing: -0.025em;
}
.tracking-wide{
  letter-spacing: 0.025em;
}
.tracking-widest{
  letter-spacing: 0.1em;
}
.text-\[\#0F172A\]{
  --tw-text-opacity: 1;
  color: rgb(15 23 42 / var(--tw-text-opacity, 1));
}
.text-\[\#0F766E\]{
  --tw-text-opacity: 1;
  color: rgb(15 118 110 / var(--tw-text-opacity, 1));
}
.text-\[\#F59E0B\]{
  --tw-text-opacity: 1;
  color: rgb(245 158 11 / var(--tw-text-opacity, 1));
}
.text-\[var\(--ink\)\]{
  color: var(--ink);
}
.text-amber-200{
  --tw-text-opacity: 1;
  color: rgb(253 230 138 / var(--tw-text-opacity, 1));
}
.text-amber-300{
  --tw-text-opacity: 1;
  color: rgb(252 211 77 / var(--tw-text-opacity, 1));
}
.text-amber-700{
  --tw-text-opacity: 1;
  color: rgb(180 83 9 / var(--tw-text-opacity, 1));
}
.text-amber-800{
  --tw-text-opacity: 1;
  color: rgb(146 64 14 / var(--tw-text-opacity, 1));
}
.text-amber-900{
  --tw-text-opacity: 1;
  color: rgb(120 53 15 / var(--tw-text-opacity, 1));
}
.text-emerald-100{
  --tw-text-opacity: 1;
  color: rgb(209 250 229 / var(--tw-text-opacity, 1));
}
.text-emerald-200{
  --tw-text-opacity: 1;
  color: rgb(167 243 208 / var(--tw-text-opacity, 1));
}
.text-emerald-300{
  --tw-text-opacity: 1;
  color: rgb(110 231 183 / var(--tw-text-opacity, 1));
}
.text-emerald-400{
  --tw-text-opacity: 1;
  color: rgb(52 211 153 / var(--tw-text-opacity, 1));
}
.text-emerald-700{
  --tw-text-opacity: 1;
  color: rgb(4 120 87 / var(--tw-text-opacity, 1));
}
.text-emerald-800{
  --tw-text-opacity: 1;
  color: rgb(6 95 70 / var(--tw-text-opacity, 1));
}
.text-red-300{
  --tw-text-opacity: 1;
  color: rgb(252 165 165 / var(--tw-text-opacity, 1));
}
.text-red-600{
  --tw-text-opacity: 1;
  color: rgb(220 38 38 / var(--tw-text-opacity, 1));
}
.text-red-700{
  --tw-text-opacity: 1;
  color: rgb(185 28 28 / var(--tw-text-opacity, 1));
}
.text-red-800{
  --tw-text-opacity: 1;
  color: rgb(153 27 27 / var(--tw-text-opacity, 1));
}
.text-slate-300{
  --tw-text-opacity: 1;
  color: rgb(203 213 225 / var(--tw-text-opacity, 1));
}
.text-slate-400{
  --tw-text-opacity: 1;
  color: rgb(148 163 184 / var(--tw-text-opacity, 1));
}
.text-slate-500{
  --tw-text-opacity: 1;
  color: rgb(100 116 139 / var(--tw-text-opacity, 1));
}
.text-slate-600{
  --tw-text-opacity: 1;
  color: rgb(71 85 105 / var(--tw-text-opacity, 1));
}
.text-slate-700{
  --tw-text-opacity: 1;
  color: rgb(51 65 85 / var(--tw-text-opacity, 1));
}
.text-slate-800{
  --tw-text-opacity: 1;
  color: rgb(30 41 59 / var(--tw-text-opacity, 1));
}
.text-slate-900{
  --tw-text-opacity: 1;
  color: rgb(15 23 42 / var(--tw-text-opacity, 1));
}
.text-teal-100{
  --tw-text-opacity: 1;
  color: rgb(204 251 241 / var(--tw-text-opacity, 1));
}
.text-teal-200{
  --tw-text-opacity: 1;
  color: rgb(153 246 228 / var(--tw-text-opacity, 1));
}
.text-teal-300{
  --tw-text-opacity: 1;
  color: rgb(94 234 212 / var(--tw-text-opacity, 1));
}
.text-teal-700{
  --tw-text-opacity: 1;
  color: rgb(15 118 110 / var(--tw-text-opacity, 1));
}
.text-white{
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity, 1));
}
.line-through{
  text-decoration-line: line-through;
}
.accent-amber-500{
  accent-color: #f59e0b;
}
.accent-emerald-600{
  accent-color: #059669;
}
.opacity-70{
  opacity: 0.7;
}
.opacity-80{
  opacity: 0.8;
}
.opacity-90{
  opacity: 0.9;
}
.shadow{
  --tw-shadow: 0 1px 3px 0 rgb(0 0 0 / 0.1), 0 1px 2px -1px rgb(0 0 0 / 0.1);
  --tw-shadow-colored: 0 1px 3px 0 var(--tw-shadow-color), 0 1px 2px -1px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}
.shadow-2xl{
  --tw-shadow: 0 25px 50px -12px rgb(0 0 0 / 0.25);
  --tw-shadow-colored: 0 25px 50px -12px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}
.shadow-\[0_20px_50px_rgba\(15\2c 23\2c 42\2c \.08\)\]{
  --tw-shadow: 0 20px 50px rgba(15,23,42,.08);
  --tw-shadow-colored: 0 20px 50px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}
.shadow-\[0_20px_60px_rgba\(15\2c 23\2c 42\2c \.10\)\]{
  --tw-shadow: 0 20px 60px rgba(15,23,42,.10);
  --tw-shadow-colored: 0 20px 60px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
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
.shadow-xl{
  --tw-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
  --tw-shadow-colored: 0 20px 25px -5px var(--tw-shadow-color), 0 8px 10px -6px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}
.outline-none{
  outline: 2px solid transparent;
  outline-offset: 2px;
}
.blur-2xl{
  --tw-blur: blur(40px);
  filter: var(--tw-blur) var(--tw-brightness) var(--tw-contrast) var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate) var(--tw-sepia) var(--tw-drop-shadow);
}
.filter{
  filter: var(--tw-blur) var(--tw-brightness) var(--tw-contrast) var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate) var(--tw-sepia) var(--tw-drop-shadow);
}
.backdrop-blur-sm{
  --tw-backdrop-blur: blur(4px);
  backdrop-filter: var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);
}
.transition-all{
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 150ms;
}
:root{
  --navy:#0F172A;
  --emerald:#0F766E;
  --teal:#14B8A6;
  --gold:#F59E0B;
  --bg:#F8FAFC;
  --surface:#ffffff;
  --ink:#0F172A;
  --muted:#64748B;
  --line:#E2E8F0;
}
@media (prefers-color-scheme: dark){
  :root{
    --bg:#0B1220;
    --surface:#111B2E;
    --ink:#F1F5F9;
    --muted:#94A3B8;
    --line:#1E293B;
  }
}
*{
  box-sizing:border-box
}
html{
  scroll-behavior:smooth
}
body{
  margin:0;
  background:var(--bg);
  color:var(--ink);
  font-family:"Plus Jakarta Sans",system-ui,-apple-system,Segoe UI,sans-serif
}
.font-display{
  font-family:"Sora",system-ui,sans-serif
}
@keyframes pulseGold{
  0%,100%{
    box-shadow:0 0 0 0 rgba(245,158,11,.55)
  }
  50%{
    box-shadow:0 0 0 14px rgba(245,158,11,0)
  }
}
.pulse-gold{
  animation:pulseGold 1.6s infinite;
  border:3px solid #F59E0B !important
}
@keyframes flashRed{
  0%,100%{
    background:#FEE2E2
  }
  50%{
    background:#EF4444;
    color:white
  }
}
.flash-red{
  animation:flashRed .8s infinite
}
@keyframes floaty{
  0%,100%{
    transform:translateY(0)
  }
  50%{
    transform:translateY(-6px)
  }
}
.floaty{
  animation:floaty 3s ease-in-out infinite
}
.no-scrollbar::-webkit-scrollbar{
  display:none
}
.hover\:scale-\[1\.02\]:hover{
  --tw-scale-x: 1.02;
  --tw-scale-y: 1.02;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}
.hover\:border-\[\#0F766E\]:hover{
  --tw-border-opacity: 1;
  border-color: rgb(15 118 110 / var(--tw-border-opacity, 1));
}
.hover\:bg-\[\#0F766E\]:hover{
  --tw-bg-opacity: 1;
  background-color: rgb(15 118 110 / var(--tw-bg-opacity, 1));
}
.hover\:bg-emerald-400:hover{
  --tw-bg-opacity: 1;
  background-color: rgb(52 211 153 / var(--tw-bg-opacity, 1));
}
.hover\:bg-red-400:hover{
  --tw-bg-opacity: 1;
  background-color: rgb(248 113 113 / var(--tw-bg-opacity, 1));
}
.hover\:bg-teal-50:hover{
  --tw-bg-opacity: 1;
  background-color: rgb(240 253 250 / var(--tw-bg-opacity, 1));
}
.focus\:border-\[\#14B8A6\]:focus{
  --tw-border-opacity: 1;
  border-color: rgb(20 184 166 / var(--tw-border-opacity, 1));
}
.active\:scale-95:active{
  --tw-scale-x: .95;
  --tw-scale-y: .95;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}
.disabled\:cursor-not-allowed:disabled{
  cursor: not-allowed;
}
.disabled\:opacity-40:disabled{
  opacity: 0.4;
}
.disabled\:opacity-50:disabled{
  opacity: 0.5;
}
@media (min-width: 640px){
  .sm\:mx-0{
    margin-left: 0px;
    margin-right: 0px;
  }
  .sm\:inline-flex{
    display: inline-flex;
  }
  .sm\:h-14{
    height: 3.5rem;
  }
  .sm\:w-14{
    width: 3.5rem;
  }
  .sm\:w-auto{
    width: auto;
  }
  .sm\:grid-cols-2{
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
  .sm\:grid-cols-3{
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }
  .sm\:grid-cols-4{
    grid-template-columns: repeat(4, minmax(0, 1fr));
  }
  .sm\:gap-3{
    gap: 0.75rem;
  }
  .sm\:p-10{
    padding: 2.5rem;
  }
  .sm\:p-12{
    padding: 3rem;
  }
  .sm\:p-7{
    padding: 1.75rem;
  }
  .sm\:p-8{
    padding: 2rem;
  }
  .sm\:p-9{
    padding: 2.25rem;
  }
  .sm\:px-6{
    padding-left: 1.5rem;
    padding-right: 1.5rem;
  }
  .sm\:py-10{
    padding-top: 2.5rem;
    padding-bottom: 2.5rem;
  }
  .sm\:py-4{
    padding-top: 1rem;
    padding-bottom: 1rem;
  }
  .sm\:text-2xl{
    font-size: 1.5rem;
    line-height: 2rem;
  }
  .sm\:text-3xl{
    font-size: 1.875rem;
    line-height: 2.25rem;
  }
  .sm\:text-\[13px\]{
    font-size: 13px;
  }
  .sm\:text-\[26px\]{
    font-size: 26px;
  }
  .sm\:text-\[28px\]{
    font-size: 28px;
  }
  .sm\:text-\[44px\]{
    font-size: 44px;
  }
  .sm\:text-base{
    font-size: 1rem;
    line-height: 1.5rem;
  }
  .sm\:text-sm{
    font-size: 0.875rem;
    line-height: 1.25rem;
  }
}
@media (min-width: 768px){
  .md\:block{
    display: block;
  }
  .md\:grid-cols-2{
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
  .md\:grid-cols-3{
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }
}
@media (min-width: 1024px){
  .lg\:grid-cols-4{
    grid-template-columns: repeat(4, minmax(0, 1fr));
  }
  .lg\:grid-cols-\[1\.15fr_1fr\]{
    grid-template-columns: 1.15fr 1fr;
  }
  .lg\:grid-cols-\[300px_1fr\]{
    grid-template-columns: 300px 1fr;
  }
  .lg\:px-10{
    padding-left: 2.5rem;
    padding-right: 2.5rem;
  }
  .lg\:text-\[32px\]{
    font-size: 32px;
  }
}
@import "https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&family=Sora:wght@700;800&display=swap";@tailwind base;@tailwind components;@tailwind utilities;:root{--navy:#0f172a;--emerald:#0f766e;--teal:#14b8a6;--gold:#f59e0b;--bg:#f8fafc;--surface:#fff;--ink:#0f172a;--muted:#64748b;--line:#e2e8f0}@media (prefers-color-scheme:dark){:root{--bg:#0b1220;--surface:#111b2e;--ink:#f1f5f9;--muted:#94a3b8;--line:#1e293b}}*{box-sizing:border-box}html{scroll-behavior:smooth}body{background:var(--bg);color:var(--ink);margin:0;font-family:Plus Jakarta Sans,system-ui,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Noto Sans,Ubuntu,Cantarell,Helvetica Neue,sans-serif}.font-display{font-family:Sora,system-ui,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Noto Sans,Ubuntu,Cantarell,Helvetica Neue,sans-serif}@keyframes pulseGold{0%,to{box-shadow:0 0 #f59e0b8c}50%{box-shadow:0 0 0 14px #f59e0b00}}.pulse-gold{animation:pulseGold 1.6s infinite;border:3px solid #f59e0b!important}@keyframes flashRed{0%,to{background:#fee2e2}50%{background:#ef4444;color:#fff}}.flash-red{animation:flashRed .8s infinite}@keyframes floaty{0%,to{transform:translateY(0)}50%{transform:translateY(-6px)}}.floaty{animation:floaty 3s ease-in-out infinite}.no-scrollbar::-webkit-scrollbar{display:none}
</style>
</head>
<body>
  <div id="root"></div>
  
  <script type="module">var Tf=Object.create;var{getPrototypeOf:Mf,defineProperty:Ua,getOwnPropertyNames:Ff}=Object;var Pf=Object.prototype.hasOwnProperty;var Xe=(e,t,n)=>{n=e!=null?Tf(Mf(e)):{};let r=t||!e||!e.__esModule?Ua(n,"default",{value:e,enumerable:!0}):n;for(let l of Ff(e))if(!Pf.call(r,l))Ua(r,l,{get:()=>e[l],enumerable:!0});return r};var nl=(e,t)=>()=>(t||e((t={exports:{}}).exports,t),t.exports);var If=(e,t)=>{for(var n in t)Ua(e,n,{get:t[n],enumerable:!0,configurable:!0,set:(r)=>t[n]=()=>r})};var Af=(e,t)=>()=>(e&&(t=e(e=0)),t);var Lt=nl((Zf)=>{var Jn=Symbol.for("react.element"),Rf=Symbol.for("react.portal"),Of=Symbol.for("react.fragment"),Df=Symbol.for("react.strict_mode"),Uf=Symbol.for("react.profiler"),Lf=Symbol.for("react.provider"),bf=Symbol.for("react.context"),Kf=Symbol.for("react.forward_ref"),Bf=Symbol.for("react.suspense"),$f=Symbol.for("react.memo"),Hf=Symbol.for("react.lazy"),ku=Symbol.iterator;function Wf(e){if(e===null||typeof e!=="object")return null;return e=ku&&e[ku]||e["@@iterator"],typeof e==="function"?e:null}var Su={isMounted:function(){return!1},enqueueForceUpdate:function(){},enqueueReplaceState:function(){},enqueueSetState:function(){}},xu=Object.assign,Eu={};function ln(e,t,n){this.props=e,this.context=t,this.refs=Eu,this.updater=n||Su}ln.prototype.isReactComponent={};ln.prototype.setState=function(e,t){if(typeof e!=="object"&&typeof e!=="function"&&e!=null)throw Error("setState(...): takes an object of state variables to update or a function which returns an object of state variables.");this.updater.enqueueSetState(this,e,t,"setState")};ln.prototype.forceUpdate=function(e){this.updater.enqueueForceUpdate(this,e,"forceUpdate")};function zu(){}zu.prototype=ln.prototype;function ba(e,t,n){this.props=e,this.context=t,this.refs=Eu,this.updater=n||Su}var Ka=ba.prototype=new zu;Ka.constructor=ba;xu(Ka,ln.prototype);Ka.isPureReactComponent=!0;var wu=Array.isArray,Cu=Object.prototype.hasOwnProperty,Ba={current:null},_u={key:!0,ref:!0,__self:!0,__source:!0};function Tu(e,t,n){var r,l={},a=null,i=null;if(t!=null)for(r in t.ref!==void 0&&(i=t.ref),t.key!==void 0&&(a=""+t.key),t)Cu.call(t,r)&&!_u.hasOwnProperty(r)&&(l[r]=t[r]);var o=arguments.length-2;if(o===1)l.children=n;else if(1<o){for(var u=Array(o),f=0;f<o;f++)u[f]=arguments[f+2];l.children=u}if(e&&e.defaultProps)for(r in o=e.defaultProps,o)l[r]===void 0&&(l[r]=o[r]);return{$$typeof:Jn,type:e,key:a,ref:i,props:l,_owner:Ba.current}}function Vf(e,t){return{$$typeof:Jn,type:e.type,key:t,ref:e.ref,props:e.props,_owner:e._owner}}function $a(e){return typeof e==="object"&&e!==null&&e.$$typeof===Jn}function Qf(e){var t={"=":"=0",":":"=2"};return"$"+e.replace(/[=:]/g,function(n){return t[n]})}var Nu=/\/+/g;function La(e,t){return typeof e==="object"&&e!==null&&e.key!=null?Qf(""+e.key):t.toString(36)}function ll(e,t,n,r,l){var a=typeof e;if(a==="undefined"||a==="boolean")e=null;var i=!1;if(e===null)i=!0;else switch(a){case"string":case"number":i=!0;break;case"object":switch(e.$$typeof){case Jn:case Rf:i=!0}}if(i)return i=e,l=l(i),e=r===""?"."+La(i,0):r,wu(l)?(n="",e!=null&&(n=e.replace(Nu,"$&/")+"/"),ll(l,t,n,"",function(f){return f})):l!=null&&($a(l)&&(l=Vf(l,n+(!l.key||i&&i.key===l.key?"":(""+l.key).replace(Nu,"$&/")+"/")+e)),t.push(l)),1;if(i=0,r=r===""?".":r+":",wu(e))for(var o=0;o<e.length;o++){a=e[o];var u=r+La(a,o);i+=ll(a,t,n,u,l)}else if(u=Wf(e),typeof u==="function")for(e=u.call(e),o=0;!(a=e.next()).done;)a=a.value,u=r+La(a,o++),i+=ll(a,t,n,u,l);else if(a==="object")throw t=String(e),Error("Objects are not valid as a React child (found: "+(t==="[object Object]"?"object with keys {"+Object.keys(e).join(", ")+"}":t)+"). If you meant to render a collection of children, use an array instead.");return i}function rl(e,t,n){if(e==null)return e;var r=[],l=0;return ll(e,r,"","",function(a){return t.call(n,a,l++)}),r}function Yf(e){if(e._status===-1){var t=e._result;t=t(),t.then(function(n){if(e._status===0||e._status===-1)e._status=1,e._result=n},function(n){if(e._status===0||e._status===-1)e._status=2,e._result=n}),e._status===-1&&(e._status=0,e._result=t)}if(e._status===1)return e._result.default;throw e._result}var se={current:null},al={transition:null},Jf={ReactCurrentDispatcher:se,ReactCurrentBatchConfig:al,ReactCurrentOwner:Ba};function Mu(){throw Error("act(...) is not supported in production builds of React.")}Zf.Children={map:rl,forEach:function(e,t,n){rl(e,function(){t.apply(this,arguments)},n)},count:function(e){var t=0;return rl(e,function(){t++}),t},toArray:function(e){return rl(e,function(t){return t})||[]},only:function(e){if(!$a(e))throw Error("React.Children.only expected to receive a single React element child.");return e}};Zf.Component=ln;Zf.Fragment=Of;Zf.Profiler=Uf;Zf.PureComponent=ba;Zf.StrictMode=Df;Zf.Suspense=Bf;Zf.__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED=Jf;Zf.act=Mu;Zf.cloneElement=function(e,t,n){if(e===null||e===void 0)throw Error("React.cloneElement(...): The argument must be a React element, but you passed "+e+".");var r=xu({},e.props),l=e.key,a=e.ref,i=e._owner;if(t!=null){if(t.ref!==void 0&&(a=t.ref,i=Ba.current),t.key!==void 0&&(l=""+t.key),e.type&&e.type.defaultProps)var o=e.type.defaultProps;for(u in t)Cu.call(t,u)&&!_u.hasOwnProperty(u)&&(r[u]=t[u]===void 0&&o!==void 0?o[u]:t[u])}var u=arguments.length-2;if(u===1)r.children=n;else if(1<u){o=Array(u);for(var f=0;f<u;f++)o[f]=arguments[f+2];r.children=o}return{$$typeof:Jn,type:e.type,key:l,ref:a,props:r,_owner:i}};Zf.createContext=function(e){return e={$$typeof:bf,_currentValue:e,_currentValue2:e,_threadCount:0,Provider:null,Consumer:null,_defaultValue:null,_globalName:null},e.Provider={$$typeof:Lf,_context:e},e.Consumer=e};Zf.createElement=Tu;Zf.createFactory=function(e){var t=Tu.bind(null,e);return t.type=e,t};Zf.createRef=function(){return{current:null}};Zf.forwardRef=function(e){return{$$typeof:Kf,render:e}};Zf.isValidElement=$a;Zf.lazy=function(e){return{$$typeof:Hf,_payload:{_status:-1,_result:e},_init:Yf}};Zf.memo=function(e,t){return{$$typeof:$f,type:e,compare:t===void 0?null:t}};Zf.startTransition=function(e){var t=al.transition;al.transition={};try{e()}finally{al.transition=t}};Zf.unstable_act=Mu;Zf.useCallback=function(e,t){return se.current.useCallback(e,t)};Zf.useContext=function(e){return se.current.useContext(e)};Zf.useDebugValue=function(){};Zf.useDeferredValue=function(e){return se.current.useDeferredValue(e)};Zf.useEffect=function(e,t){return se.current.useEffect(e,t)};Zf.useId=function(){return se.current.useId()};Zf.useImperativeHandle=function(e,t,n){return se.current.useImperativeHandle(e,t,n)};Zf.useInsertionEffect=function(e,t){return se.current.useInsertionEffect(e,t)};Zf.useLayoutEffect=function(e,t){return se.current.useLayoutEffect(e,t)};Zf.useMemo=function(e,t){return se.current.useMemo(e,t)};Zf.useReducer=function(e,t,n){return se.current.useReducer(e,t,n)};Zf.useRef=function(e){return se.current.useRef(e)};Zf.useState=function(e){return se.current.useState(e)};Zf.useSyncExternalStore=function(e,t,n){return se.current.useSyncExternalStore(e,t,n)};Zf.useTransition=function(){return se.current.useTransition()};Zf.version="18.3.1"});var Du=nl((Ap)=>{function Wa(e,t){var n=e.length;e.push(t);e:for(;0<n;){var r=n-1>>>1,l=e[r];if(0<il(l,t))e[r]=t,e[n]=l,n=r;else break e}}function De(e){return e.length===0?null:e[0]}function dl(e){if(e.length===0)return null;var t=e[0],n=e.pop();if(n!==t){e[0]=n;e:for(var r=0,l=e.length,a=l>>>1;r<a;){var i=2*(r+1)-1,o=e[i],u=i+1,f=e[u];if(0>il(o,n))u<l&&0>il(f,o)?(e[r]=f,e[u]=n,r=u):(e[r]=o,e[i]=n,r=i);else if(u<l&&0>il(f,n))e[r]=f,e[u]=n,r=u;else break e}}return t}function il(e,t){var n=e.sortIndex-t.sortIndex;return n!==0?n:e.id-t.id}if(typeof performance==="object"&&typeof performance.now==="function")Va=performance,Ap.unstable_now=function(){return Va.now()};else ol=Date,Qa=ol.now(),Ap.unstable_now=function(){return ol.now()-Qa};var Va,ol,Qa,Ve=[],dt=[],Ip=1,Te=null,le=3,cl=!1,bt=!1,Gn=!1,Pu=typeof setTimeout==="function"?setTimeout:null,Iu=typeof clearTimeout==="function"?clearTimeout:null,Fu=typeof setImmediate<"u"?setImmediate:null;typeof navigator<"u"&&navigator.scheduling!==void 0&&navigator.scheduling.isInputPending!==void 0&&navigator.scheduling.isInputPending.bind(navigator.scheduling);function Ya(e){for(var t=De(dt);t!==null;){if(t.callback===null)dl(dt);else if(t.startTime<=e)dl(dt),t.sortIndex=t.expirationTime,Wa(Ve,t);else break;t=De(dt)}}function Za(e){if(Gn=!1,Ya(e),!bt)if(De(Ve)!==null)bt=!0,Xa(Ga);else{var t=De(dt);t!==null&&qa(Za,t.startTime-e)}}function Ga(e,t){bt=!1,Gn&&(Gn=!1,Iu(Xn),Xn=-1),cl=!0;var n=le;try{Ya(t);for(Te=De(Ve);Te!==null&&(!(Te.expirationTime>t)||e&&!Ou());){var r=Te.callback;if(typeof r==="function"){Te.callback=null,le=Te.priorityLevel;var l=r(Te.expirationTime<=t);t=Ap.unstable_now(),typeof l==="function"?Te.callback=l:Te===De(Ve)&&dl(Ve),Ya(t)}else dl(Ve);Te=De(Ve)}if(Te!==null)var a=!0;else{var i=De(dt);i!==null&&qa(Za,i.startTime-t),a=!1}return a}finally{Te=null,le=n,cl=!1}}var fl=!1,ul=null,Xn=-1,Au=5,Ru=-1;function Ou(){return Ap.unstable_now()-Ru<Au?!1:!0}function Ha(){if(ul!==null){var e=Ap.unstable_now();Ru=e;var t=!0;try{t=ul(!0,e)}finally{t?Zn():(fl=!1,ul=null)}}else fl=!1}var Zn;if(typeof Fu==="function")Zn=function(){Fu(Ha)};else if(typeof MessageChannel<"u")sl=new MessageChannel,Ja=sl.port2,sl.port1.onmessage=Ha,Zn=function(){Ja.postMessage(null)};else Zn=function(){Pu(Ha,0)};var sl,Ja;function Xa(e){ul=e,fl||(fl=!0,Zn())}function qa(e,t){Xn=Pu(function(){e(Ap.unstable_now())},t)}Ap.unstable_IdlePriority=5;Ap.unstable_ImmediatePriority=1;Ap.unstable_LowPriority=4;Ap.unstable_NormalPriority=3;Ap.unstable_Profiling=null;Ap.unstable_UserBlockingPriority=2;Ap.unstable_cancelCallback=function(e){e.callback=null};Ap.unstable_continueExecution=function(){bt||cl||(bt=!0,Xa(Ga))};Ap.unstable_forceFrameRate=function(e){0>e||125<e?console.error("forceFrameRate takes a positive int between 0 and 125, forcing frame rates higher than 125 fps is not supported"):Au=0<e?Math.floor(1000/e):5};Ap.unstable_getCurrentPriorityLevel=function(){return le};Ap.unstable_getFirstCallbackNode=function(){return De(Ve)};Ap.unstable_next=function(e){switch(le){case 1:case 2:case 3:var t=3;break;default:t=le}var n=le;le=t;try{return e()}finally{le=n}};Ap.unstable_pauseExecution=function(){};Ap.unstable_requestPaint=function(){};Ap.unstable_runWithPriority=function(e,t){switch(e){case 1:case 2:case 3:case 4:case 5:break;default:e=3}var n=le;le=e;try{return t()}finally{le=n}};Ap.unstable_scheduleCallback=function(e,t,n){var r=Ap.unstable_now();switch(typeof n==="object"&&n!==null?(n=n.delay,n=typeof n==="number"&&0<n?r+n:r):n=r,e){case 1:var l=-1;break;case 2:l=250;break;case 5:l=1073741823;break;case 4:l=1e4;break;default:l=5000}return l=n+l,e={id:Ip++,callback:t,priorityLevel:e,startTime:n,expirationTime:l,sortIndex:-1},n>r?(e.sortIndex=n,Wa(dt,e),De(Ve)===null&&e===De(dt)&&(Gn?(Iu(Xn),Xn=-1):Gn=!0,qa(Za,n-r))):(e.sortIndex=l,Wa(Ve,e),bt||cl||(bt=!0,Xa(Ga))),e};Ap.unstable_shouldYield=Ou;Ap.unstable_wrapCallback=function(e){var t=le;return function(){var n=le;le=t;try{return e.apply(this,arguments)}finally{le=n}}}});var au={};If(au,{version:()=>Gc,unstable_renderSubtreeIntoContainer:()=>Zc,unstable_batchedUpdates:()=>Jc,unmountComponentAtNode:()=>Yc,render:()=>Qc,hydrateRoot:()=>Vc,hydrate:()=>Wc,flushSync:()=>Hc,findDOMNode:()=>$c,createRoot:()=>Bc,createPortal:()=>Kc,__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED:()=>bc});function w(e){for(var t="https://reactjs.org/docs/error-decoder.html?invariant="+e,n=1;n<arguments.length;n++)t+="&args[]="+encodeURIComponent(arguments[n]);return"Minified React error #"+e+"; visit "+t+" for the full message or use the non-minified dev environment for full errors and additional helpful warnings."}function jt(e,t){_n(e,t),_n(e+"Capture",t)}function _n(e,t){Sr[e]=t;for(e=0;e<t.length;e++)$s.add(t[e])}function jp(e){if(wi.call(Lu,e))return!0;if(wi.call(Uu,e))return!1;if(qp.test(e))return Lu[e]=!0;return Uu[e]=!0,!1}function em(e,t,n,r){if(n!==null&&n.type===0)return!1;switch(typeof t){case"function":case"symbol":return!0;case"boolean":if(r)return!1;if(n!==null)return!n.acceptsBooleans;return e=e.toLowerCase().slice(0,5),e!=="data-"&&e!=="aria-";default:return!1}}function tm(e,t,n,r){if(t===null||typeof t>"u"||em(e,t,n,r))return!0;if(r)return!1;if(n!==null)switch(n.type){case 3:return!t;case 4:return t===!1;case 5:return isNaN(t);case 6:return isNaN(t)||1>t}return!1}function fe(e,t,n,r,l,a,i){this.acceptsBooleans=t===2||t===3||t===4,this.attributeName=r,this.attributeNamespace=l,this.mustUseProperty=n,this.propertyName=e,this.type=t,this.sanitizeURL=a,this.removeEmptyString=i}function vo(e){return e[1].toUpperCase()}function go(e,t,n,r){var l=re.hasOwnProperty(t)?re[t]:null;if(l!==null?l.type!==0:r||!(2<t.length)||t[0]!=="o"&&t[0]!=="O"||t[1]!=="n"&&t[1]!=="N")tm(t,n,l,r)&&(n=null),r||l===null?jp(t)&&(n===null?e.removeAttribute(t):e.setAttribute(t,""+n)):l.mustUseProperty?e[l.propertyName]=n===null?l.type===3?!1:"":n:(t=l.attributeName,r=l.attributeNamespace,n===null?e.removeAttribute(t):(l=l.type,n=l===3||l===4&&n===!0?"":""+n,r?e.setAttributeNS(r,t,n):e.setAttribute(t,n)))}function qn(e){if(e===null||typeof e!=="object")return null;return e=bu&&e[bu]||e["@@iterator"],typeof e==="function"?e:null}function ar(e){if(ja===void 0)try{throw Error()}catch(n){var t=n.stack.trim().match(/\n( *(at )?)/);ja=t&&t[1]||""}return`
`+ja+e}function ti(e,t){if(!e||ei)return"";ei=!0;var n=Error.prepareStackTrace;Error.prepareStackTrace=void 0;try{if(t)if(t=function(){throw Error()},Object.defineProperty(t.prototype,"props",{set:function(){throw Error()}}),typeof Reflect==="object"&&Reflect.construct){try{Reflect.construct(t,[])}catch(f){var r=f}Reflect.construct(e,[],t)}else{try{t.call()}catch(f){r=f}e.call(t.prototype)}else{try{throw Error()}catch(f){r=f}e()}}catch(f){if(f&&r&&typeof f.stack==="string"){for(var l=f.stack.split(`
`),a=r.stack.split(`
`),i=l.length-1,o=a.length-1;1<=i&&0<=o&&l[i]!==a[o];)o--;for(;1<=i&&0<=o;i--,o--)if(l[i]!==a[o]){if(i!==1||o!==1)do if(i--,o--,0>o||l[i]!==a[o]){var u=`
`+l[i].replace(" at new "," at ");return e.displayName&&u.includes("<anonymous>")&&(u=u.replace("<anonymous>",e.displayName)),u}while(1<=i&&0<=o);break}}}finally{ei=!1,Error.prepareStackTrace=n}return(e=e?e.displayName||e.name:"")?ar(e):""}function nm(e){switch(e.tag){case 5:return ar(e.type);case 16:return ar("Lazy");case 13:return ar("Suspense");case 19:return ar("SuspenseList");case 0:case 2:case 15:return e=ti(e.type,!1),e;case 11:return e=ti(e.type.render,!1),e;case 1:return e=ti(e.type,!0),e;default:return""}}function Ei(e){if(e==null)return null;if(typeof e==="function")return e.displayName||e.name||null;if(typeof e==="string")return e;switch(e){case dn:return"Fragment";case sn:return"Portal";case Ni:return"Profiler";case yo:return"StrictMode";case Si:return"Suspense";case xi:return"SuspenseList"}if(typeof e==="object")switch(e.$$typeof){case Ws:return(e.displayName||"Context")+".Consumer";case Hs:return(e._context.displayName||"Context")+".Provider";case ko:var t=e.render;return e=e.displayName,e||(e=t.displayName||t.name||"",e=e!==""?"ForwardRef("+e+")":"ForwardRef"),e;case wo:return t=e.displayName||null,t!==null?t:Ei(e.type)||"Memo";case ft:t=e._payload,e=e._init;try{return Ei(e(t))}catch(n){}}return null}function rm(e){var t=e.type;switch(e.tag){case 24:return"Cache";case 9:return(t.displayName||"Context")+".Consumer";case 10:return(t._context.displayName||"Context")+".Provider";case 18:return"DehydratedFragment";case 11:return e=t.render,e=e.displayName||e.name||"",t.displayName||(e!==""?"ForwardRef("+e+")":"ForwardRef");case 7:return"Fragment";case 5:return t;case 4:return"Portal";case 3:return"Root";case 6:return"Text";case 16:return Ei(t);case 8:return t===yo?"StrictMode":"Mode";case 22:return"Offscreen";case 12:return"Profiler";case 21:return"Scope";case 13:return"Suspense";case 19:return"SuspenseList";case 25:return"TracingMarker";case 1:case 0:case 17:case 2:case 14:case 15:if(typeof t==="function")return t.displayName||t.name||null;if(typeof t==="string")return t}return null}function Ct(e){switch(typeof e){case"boolean":case"number":case"string":case"undefined":return e;case"object":return e;default:return""}}function Qs(e){var t=e.type;return(e=e.nodeName)&&e.toLowerCase()==="input"&&(t==="checkbox"||t==="radio")}function lm(e){var t=Qs(e)?"checked":"value",n=Object.getOwnPropertyDescriptor(e.constructor.prototype,t),r=""+e[t];if(!e.hasOwnProperty(t)&&typeof n<"u"&&typeof n.get==="function"&&typeof n.set==="function"){var{get:l,set:a}=n;return Object.defineProperty(e,t,{configurable:!0,get:function(){return l.call(this)},set:function(i){r=""+i,a.call(this,i)}}),Object.defineProperty(e,t,{enumerable:n.enumerable}),{getValue:function(){return r},setValue:function(i){r=""+i},stopTracking:function(){e._valueTracker=null,delete e[t]}}}}function ml(e){e._valueTracker||(e._valueTracker=lm(e))}function Ys(e){if(!e)return!1;var t=e._valueTracker;if(!t)return!0;var n=t.getValue(),r="";return e&&(r=Qs(e)?e.checked?"true":"false":e.value),e=r,e!==n?(t.setValue(e),!0):!1}function bl(e){if(e=e||(typeof document<"u"?document:void 0),typeof e>"u")return null;try{return e.activeElement||e.body}catch(t){return e.body}}function zi(e,t){var n=t.checked;return V({},t,{defaultChecked:void 0,defaultValue:void 0,value:void 0,checked:n!=null?n:e._wrapperState.initialChecked})}function Ku(e,t){var n=t.defaultValue==null?"":t.defaultValue,r=t.checked!=null?t.checked:t.defaultChecked;n=Ct(t.value!=null?t.value:n),e._wrapperState={initialChecked:r,initialValue:n,controlled:t.type==="checkbox"||t.type==="radio"?t.checked!=null:t.value!=null}}function Js(e,t){t=t.checked,t!=null&&go(e,"checked",t,!1)}function Ci(e,t){Js(e,t);var n=Ct(t.value),r=t.type;if(n!=null)if(r==="number"){if(n===0&&e.value===""||e.value!=n)e.value=""+n}else e.value!==""+n&&(e.value=""+n);else if(r==="submit"||r==="reset"){e.removeAttribute("value");return}t.hasOwnProperty("value")?_i(e,t.type,n):t.hasOwnProperty("defaultValue")&&_i(e,t.type,Ct(t.defaultValue)),t.checked==null&&t.defaultChecked!=null&&(e.defaultChecked=!!t.defaultChecked)}function Bu(e,t,n){if(t.hasOwnProperty("value")||t.hasOwnProperty("defaultValue")){var r=t.type;if(!(r!=="submit"&&r!=="reset"||t.value!==void 0&&t.value!==null))return;t=""+e._wrapperState.initialValue,n||t===e.value||(e.value=t),e.defaultValue=t}n=e.name,n!==""&&(e.name=""),e.defaultChecked=!!e._wrapperState.initialChecked,n!==""&&(e.name=n)}function _i(e,t,n){if(t!=="number"||bl(e.ownerDocument)!==e)n==null?e.defaultValue=""+e._wrapperState.initialValue:e.defaultValue!==""+n&&(e.defaultValue=""+n)}function Nn(e,t,n,r){if(e=e.options,t){t={};for(var l=0;l<n.length;l++)t["$"+n[l]]=!0;for(n=0;n<e.length;n++)l=t.hasOwnProperty("$"+e[n].value),e[n].selected!==l&&(e[n].selected=l),l&&r&&(e[n].defaultSelected=!0)}else{n=""+Ct(n),t=null;for(l=0;l<e.length;l++){if(e[l].value===n){e[l].selected=!0,r&&(e[l].defaultSelected=!0);return}t!==null||e[l].disabled||(t=e[l])}t!==null&&(t.selected=!0)}}function Ti(e,t){if(t.dangerouslySetInnerHTML!=null)throw Error(w(91));return V({},t,{value:void 0,defaultValue:void 0,children:""+e._wrapperState.initialValue})}function $u(e,t){var n=t.value;if(n==null){if(n=t.children,t=t.defaultValue,n!=null){if(t!=null)throw Error(w(92));if(ir(n)){if(1<n.length)throw Error(w(93));n=n[0]}t=n}t==null&&(t=""),n=t}e._wrapperState={initialValue:Ct(n)}}function Zs(e,t){var n=Ct(t.value),r=Ct(t.defaultValue);n!=null&&(n=""+n,n!==e.value&&(e.value=n),t.defaultValue==null&&e.defaultValue!==n&&(e.defaultValue=n)),r!=null&&(e.defaultValue=""+r)}function Hu(e){var t=e.textContent;t===e._wrapperState.initialValue&&t!==""&&t!==null&&(e.value=t)}function Gs(e){switch(e){case"svg":return"http://www.w3.org/2000/svg";case"math":return"http://www.w3.org/1998/Math/MathML";default:return"http://www.w3.org/1999/xhtml"}}function Mi(e,t){return e==null||e==="http://www.w3.org/1999/xhtml"?Gs(t):e==="http://www.w3.org/2000/svg"&&t==="foreignObject"?"http://www.w3.org/1999/xhtml":e}function xr(e,t){if(t){var n=e.firstChild;if(n&&n===e.lastChild&&n.nodeType===3){n.nodeValue=t;return}}e.textContent=t}function qs(e,t,n){return t==null||typeof t==="boolean"||t===""?"":n||typeof t!=="number"||t===0||pr.hasOwnProperty(e)&&pr[e]?(""+t).trim():t+"px"}function js(e,t){e=e.style;for(var n in t)if(t.hasOwnProperty(n)){var r=n.indexOf("--")===0,l=qs(n,t[n],r);n==="float"&&(n="cssFloat"),r?e.setProperty(n,l):e[n]=l}}function Fi(e,t){if(t){if(im[e]&&(t.children!=null||t.dangerouslySetInnerHTML!=null))throw Error(w(137,e));if(t.dangerouslySetInnerHTML!=null){if(t.children!=null)throw Error(w(60));if(typeof t.dangerouslySetInnerHTML!=="object"||!("__html"in t.dangerouslySetInnerHTML))throw Error(w(61))}if(t.style!=null&&typeof t.style!=="object")throw Error(w(62))}}function Pi(e,t){if(e.indexOf("-")===-1)return typeof t.is==="string";switch(e){case"annotation-xml":case"color-profile":case"font-face":case"font-face-src":case"font-face-uri":case"font-face-format":case"font-face-name":case"missing-glyph":return!1;default:return!0}}function No(e){return e=e.target||e.srcElement||window,e.correspondingUseElement&&(e=e.correspondingUseElement),e.nodeType===3?e.parentNode:e}function Wu(e){if(e=Br(e)){if(typeof Ai!=="function")throw Error(w(280));var t=e.stateNode;t&&(t=pa(t),Ai(e.stateNode,e.type,t))}}function ed(e){Sn?xn?xn.push(e):xn=[e]:Sn=e}function td(){if(Sn){var e=Sn,t=xn;if(xn=Sn=null,Wu(e),t)for(e=0;e<t.length;e++)Wu(t[e])}}function nd(e,t){return e(t)}function rd(){}function ld(e,t,n){if(ni)return e(t,n);ni=!0;try{return nd(e,t,n)}finally{if(ni=!1,Sn!==null||xn!==null)rd(),td()}}function Er(e,t){var n=e.stateNode;if(n===null)return null;var r=pa(n);if(r===null)return null;n=r[t];e:switch(t){case"onClick":case"onClickCapture":case"onDoubleClick":case"onDoubleClickCapture":case"onMouseDown":case"onMouseDownCapture":case"onMouseMove":case"onMouseMoveCapture":case"onMouseUp":case"onMouseUpCapture":case"onMouseEnter":(r=!r.disabled)||(e=e.type,r=!(e==="button"||e==="input"||e==="select"||e==="textarea")),e=!r;break e;default:e=!1}if(e)return null;if(n&&typeof n!=="function")throw Error(w(231,t,typeof n));return n}function om(e,t,n,r,l,a,i,o,u){var f=Array.prototype.slice.call(arguments,3);try{t.apply(n,f)}catch(h){this.onError(h)}}function sm(e,t,n,r,l,a,i,o,u){mr=!1,Kl=null,om.apply(um,arguments)}function dm(e,t,n,r,l,a,i,o,u){if(sm.apply(this,arguments),mr){if(mr){var f=Kl;mr=!1,Kl=null}else throw Error(w(198));Bl||(Bl=!0,Oi=f)}}function en(e){var t=e,n=e;if(e.alternate)for(;t.return;)t=t.return;else{e=t;do t=e,(t.flags&4098)!==0&&(n=t.return),e=t.return;while(e)}return t.tag===3?n:null}function ad(e){if(e.tag===13){var t=e.memoizedState;if(t===null&&(e=e.alternate,e!==null&&(t=e.memoizedState)),t!==null)return t.dehydrated}return null}function Vu(e){if(en(e)!==e)throw Error(w(188))}function cm(e){var t=e.alternate;if(!t){if(t=en(e),t===null)throw Error(w(188));return t!==e?null:e}for(var n=e,r=t;;){var l=n.return;if(l===null)break;var a=l.alternate;if(a===null){if(r=l.return,r!==null){n=r;continue}break}if(l.child===a.child){for(a=l.child;a;){if(a===n)return Vu(l),e;if(a===r)return Vu(l),t;a=a.sibling}throw Error(w(188))}if(n.return!==r.return)n=l,r=a;else{for(var i=!1,o=l.child;o;){if(o===n){i=!0,n=l,r=a;break}if(o===r){i=!0,r=l,n=a;break}o=o.sibling}if(!i){for(o=a.child;o;){if(o===n){i=!0,n=a,r=l;break}if(o===r){i=!0,r=a,n=l;break}o=o.sibling}if(!i)throw Error(w(189))}}if(n.alternate!==r)throw Error(w(190))}if(n.tag!==3)throw Error(w(188));return n.stateNode.current===n?e:t}function id(e){return e=cm(e),e!==null?od(e):null}function od(e){if(e.tag===5||e.tag===6)return e;for(e=e.child;e!==null;){var t=od(e);if(t!==null)return t;e=e.sibling}return null}function vm(e){if(Ze&&typeof Ze.onCommitFiberRoot==="function")try{Ze.onCommitFiberRoot(sa,e,void 0,(e.current.flags&128)===128)}catch(t){}}function km(e){return e>>>=0,e===0?32:31-(gm(e)/ym|0)|0}function or(e){switch(e&-e){case 1:return 1;case 2:return 2;case 4:return 4;case 8:return 8;case 16:return 16;case 32:return 32;case 64:case 128:case 256:case 512:case 1024:case 2048:case 4096:case 8192:case 16384:case 32768:case 65536:case 131072:case 262144:case 524288:case 1048576:case 2097152:return e&4194240;case 4194304:case 8388608:case 16777216:case 33554432:case 67108864:return e&130023424;case 134217728:return 134217728;case 268435456:return 268435456;case 536870912:return 536870912;case 1073741824:return 1073741824;default:return e}}function Hl(e,t){var n=e.pendingLanes;if(n===0)return 0;var r=0,l=e.suspendedLanes,a=e.pingedLanes,i=n&268435455;if(i!==0){var o=i&~l;o!==0?r=or(o):(a&=i,a!==0&&(r=or(a)))}else i=n&~l,i!==0?r=or(i):a!==0&&(r=or(a));if(r===0)return 0;if(t!==0&&t!==r&&(t&l)===0&&(l=r&-r,a=t&-t,l>=a||l===16&&(a&4194240)!==0))return t;if((r&4)!==0&&(r|=n&16),t=e.entangledLanes,t!==0)for(e=e.entanglements,t&=r;0<t;)n=31-Be(t),l=1<<n,r|=e[n],t&=~l;return r}function wm(e,t){switch(e){case 1:case 2:case 4:return t+250;case 8:case 16:case 32:case 64:case 128:case 256:case 512:case 1024:case 2048:case 4096:case 8192:case 16384:case 32768:case 65536:case 131072:case 262144:case 524288:case 1048576:case 2097152:return t+5000;case 4194304:case 8388608:case 16777216:case 33554432:case 67108864:return-1;case 134217728:case 268435456:case 536870912:case 1073741824:return-1;default:return-1}}function Nm(e,t){for(var{suspendedLanes:n,pingedLanes:r,expirationTimes:l,pendingLanes:a}=e;0<a;){var i=31-Be(a),o=1<<i,u=l[i];if(u===-1){if((o&n)===0||(o&r)!==0)l[i]=wm(o,t)}else u<=t&&(e.expiredLanes|=o);a&=~o}}function Di(e){return e=e.pendingLanes&-1073741825,e!==0?e:e&1073741824?1073741824:0}function cd(){var e=vl;return vl<<=1,(vl&4194240)===0&&(vl=64),e}function ri(e){for(var t=[],n=0;31>n;n++)t.push(e);return t}function br(e,t,n){e.pendingLanes|=t,t!==536870912&&(e.suspendedLanes=0,e.pingedLanes=0),e=e.eventTimes,t=31-Be(t),e[t]=n}function Sm(e,t){var n=e.pendingLanes&~t;e.pendingLanes=t,e.suspendedLanes=0,e.pingedLanes=0,e.expiredLanes&=t,e.mutableReadLanes&=t,e.entangledLanes&=t,t=e.entanglements;var r=e.eventTimes;for(e=e.expirationTimes;0<n;){var l=31-Be(n),a=1<<l;t[l]=0,r[l]=-1,e[l]=-1,n&=~a}}function xo(e,t){var n=e.entangledLanes|=t;for(e=e.entanglements;n;){var r=31-Be(n),l=1<<r;l&t|e[r]&t&&(e[r]|=t),n&=~l}}function fd(e){return e&=-e,1<e?4<e?(e&268435455)!==0?16:536870912:4:1}function Yu(e,t){switch(e){case"focusin":case"focusout":yt=null;break;case"dragenter":case"dragleave":kt=null;break;case"mouseover":case"mouseout":wt=null;break;case"pointerover":case"pointerout":zr.delete(t.pointerId);break;case"gotpointercapture":case"lostpointercapture":Cr.delete(t.pointerId)}}function jn(e,t,n,r,l,a){if(e===null||e.nativeEvent!==a)return e={blockedOn:t,domEventName:n,eventSystemFlags:r,nativeEvent:a,targetContainers:[l]},t!==null&&(t=Br(t),t!==null&&Eo(t)),e;return e.eventSystemFlags|=r,t=e.targetContainers,l!==null&&t.indexOf(l)===-1&&t.push(l),e}function Em(e,t,n,r,l){switch(t){case"focusin":return yt=jn(yt,e,t,n,r,l),!0;case"dragenter":return kt=jn(kt,e,t,n,r,l),!0;case"mouseover":return wt=jn(wt,e,t,n,r,l),!0;case"pointerover":var a=l.pointerId;return zr.set(a,jn(zr.get(a)||null,e,t,n,r,l)),!0;case"gotpointercapture":return a=l.pointerId,Cr.set(a,jn(Cr.get(a)||null,e,t,n,r,l)),!0}return!1}function gd(e){var t=Ht(e.target);if(t!==null){var n=en(t);if(n!==null){if(t=n.tag,t===13){if(t=ad(n),t!==null){e.blockedOn=t,vd(e.priority,function(){md(n)});return}}else if(t===3&&n.stateNode.current.memoizedState.isDehydrated){e.blockedOn=n.tag===3?n.stateNode.containerInfo:null;return}}}e.blockedOn=null}function Tl(e){if(e.blockedOn!==null)return!1;for(var t=e.targetContainers;0<t.length;){var n=Li(e.domEventName,e.eventSystemFlags,t[0],e.nativeEvent);if(n===null){n=e.nativeEvent;var r=new n.constructor(n.type,n);Ii=r,n.target.dispatchEvent(r),Ii=null}else return t=Br(n),t!==null&&Eo(t),e.blockedOn=n,!1;t.shift()}return!0}function Ju(e,t,n){Tl(e)&&n.delete(t)}function zm(){Ui=!1,yt!==null&&Tl(yt)&&(yt=null),kt!==null&&Tl(kt)&&(kt=null),wt!==null&&Tl(wt)&&(wt=null),zr.forEach(Ju),Cr.forEach(Ju)}function er(e,t){e.blockedOn===t&&(e.blockedOn=null,Ui||(Ui=!0,K.unstable_scheduleCallback(K.unstable_NormalPriority,zm)))}function _r(e){function t(l){return er(l,e)}if(0<yl.length){er(yl[0],e);for(var n=1;n<yl.length;n++){var r=yl[n];r.blockedOn===e&&(r.blockedOn=null)}}yt!==null&&er(yt,e),kt!==null&&er(kt,e),wt!==null&&er(wt,e),zr.forEach(t),Cr.forEach(t);for(n=0;n<mt.length;n++)r=mt[n],r.blockedOn===e&&(r.blockedOn=null);for(;0<mt.length&&(n=mt[0],n.blockedOn===null);)gd(n),n.blockedOn===null&&mt.shift()}function Cm(e,t,n,r){var l=O,a=En.transition;En.transition=null;try{O=1,zo(e,t,n,r)}finally{O=l,En.transition=a}}function _m(e,t,n,r){var l=O,a=En.transition;En.transition=null;try{O=4,zo(e,t,n,r)}finally{O=l,En.transition=a}}function zo(e,t,n,r){if(Wl){var l=Li(e,t,n,r);if(l===null)si(e,t,r,Vl,n),Yu(e,r);else if(Em(l,e,t,n,r))r.stopPropagation();else if(Yu(e,r),t&4&&-1<xm.indexOf(e)){for(;l!==null;){var a=Br(l);if(a!==null&&pd(a),a=Li(e,t,n,r),a===null&&si(e,t,r,Vl,n),a===l)break;l=a}l!==null&&r.stopPropagation()}else si(e,t,r,null,n)}}function Li(e,t,n,r){if(Vl=null,e=No(r),e=Ht(e),e!==null)if(t=en(e),t===null)e=null;else if(n=t.tag,n===13){if(e=ad(t),e!==null)return e;e=null}else if(n===3){if(t.stateNode.current.memoizedState.isDehydrated)return t.tag===3?t.stateNode.containerInfo:null;e=null}else t!==e&&(e=null);return Vl=e,null}function yd(e){switch(e){case"cancel":case"click":case"close":case"contextmenu":case"copy":case"cut":case"auxclick":case"dblclick":case"dragend":case"dragstart":case"drop":case"focusin":case"focusout":case"input":case"invalid":case"keydown":case"keypress":case"keyup":case"mousedown":case"mouseup":case"paste":case"pause":case"play":case"pointercancel":case"pointerdown":case"pointerup":case"ratechange":case"reset":case"resize":case"seeked":case"submit":case"touchcancel":case"touchend":case"touchstart":case"volumechange":case"change":case"selectionchange":case"textInput":case"compositionstart":case"compositionend":case"compositionupdate":case"beforeblur":case"afterblur":case"beforeinput":case"blur":case"fullscreenchange":case"focus":case"hashchange":case"popstate":case"select":case"selectstart":return 1;case"drag":case"dragenter":case"dragexit":case"dragleave":case"dragover":case"mousemove":case"mouseout":case"mouseover":case"pointermove":case"pointerout":case"pointerover":case"scroll":case"toggle":case"touchmove":case"wheel":case"mouseenter":case"mouseleave":case"pointerenter":case"pointerleave":return 4;case"message":switch(mm()){case So:return 1;case sd:return 4;case $l:case hm:return 16;case dd:return 536870912;default:return 16}default:return 16}}function kd(){if(Ml)return Ml;var e,t=Co,n=t.length,r,l="value"in vt?vt.value:vt.textContent,a=l.length;for(e=0;e<n&&t[e]===l[e];e++);var i=n-e;for(r=1;r<=i&&t[n-r]===l[a-r];r++);return Ml=l.slice(e,1<r?1-r:void 0)}function Fl(e){var t=e.keyCode;return"charCode"in e?(e=e.charCode,e===0&&t===13&&(e=13)):e=t,e===10&&(e=13),32<=e||e===13?e:0}function kl(){return!0}function Zu(){return!1}function Ce(e){function t(n,r,l,a,i){this._reactName=n,this._targetInst=l,this.type=r,this.nativeEvent=a,this.target=i,this.currentTarget=null;for(var o in e)e.hasOwnProperty(o)&&(n=e[o],this[o]=n?n(a):a[o]);return this.isDefaultPrevented=(a.defaultPrevented!=null?a.defaultPrevented:a.returnValue===!1)?kl:Zu,this.isPropagationStopped=Zu,this}return V(t.prototype,{preventDefault:function(){this.defaultPrevented=!0;var n=this.nativeEvent;n&&(n.preventDefault?n.preventDefault():typeof n.returnValue!=="unknown"&&(n.returnValue=!1),this.isDefaultPrevented=kl)},stopPropagation:function(){var n=this.nativeEvent;n&&(n.stopPropagation?n.stopPropagation():typeof n.cancelBubble!=="unknown"&&(n.cancelBubble=!0),this.isPropagationStopped=kl)},persist:function(){},isPersistent:kl}),t}function Km(e){var t=this.nativeEvent;return t.getModifierState?t.getModifierState(e):(e=bm[e])?!!t[e]:!1}function To(){return Km}function Nd(e,t){switch(e){case"keyup":return Gm.indexOf(t.keyCode)!==-1;case"keydown":return t.keyCode!==229;case"keypress":case"mousedown":case"focusout":return!0;default:return!1}}function Sd(e){return e=e.detail,typeof e==="object"&&"data"in e?e.data:null}function qm(e,t){switch(e){case"compositionend":return Sd(t);case"keypress":if(t.which!==32)return null;return es=!0,ju;case"textInput":return e=t.data,e===ju&&es?null:e;default:return null}}function jm(e,t){if(cn)return e==="compositionend"||!Mo&&Nd(e,t)?(e=kd(),Ml=Co=vt=null,cn=!1,e):null;switch(e){case"paste":return null;case"keypress":if(!(t.ctrlKey||t.altKey||t.metaKey)||t.ctrlKey&&t.altKey){if(t.char&&1<t.char.length)return t.char;if(t.which)return String.fromCharCode(t.which)}return null;case"compositionend":return wd&&t.locale!=="ko"?null:t.data;default:return null}}function ts(e){var t=e&&e.nodeName&&e.nodeName.toLowerCase();return t==="input"?!!e0[e.type]:t==="textarea"?!0:!1}function xd(e,t,n,r){ed(r),t=Ql(t,"onChange"),0<t.length&&(n=new _o("onChange","change",null,n,r),e.push({event:n,listeners:t}))}function t0(e){Rd(e,0)}function ca(e){var t=mn(e);if(Ys(t))return e}function n0(e,t){if(e==="change")return t}function ns(){vr&&(vr.detachEvent("onpropertychange",zd),Tr=vr=null)}function zd(e){if(e.propertyName==="value"&&ca(Tr)){var t=[];xd(t,Tr,e,No(e)),ld(t0,t)}}function r0(e,t,n){e==="focusin"?(ns(),vr=t,Tr=n,vr.attachEvent("onpropertychange",zd)):e==="focusout"&&ns()}function l0(e){if(e==="selectionchange"||e==="keyup"||e==="keydown")return ca(Tr)}function a0(e,t){if(e==="click")return ca(t)}function i0(e,t){if(e==="input"||e==="change")return ca(t)}function o0(e,t){return e===t&&(e!==0||1/e===1/t)||e!==e&&t!==t}function Mr(e,t){if(He(e,t))return!0;if(typeof e!=="object"||e===null||typeof t!=="object"||t===null)return!1;var n=Object.keys(e),r=Object.keys(t);if(n.length!==r.length)return!1;for(r=0;r<n.length;r++){var l=n[r];if(!wi.call(t,l)||!He(e[l],t[l]))return!1}return!0}function rs(e){for(;e&&e.firstChild;)e=e.firstChild;return e}function ls(e,t){var n=rs(e);e=0;for(var r;n;){if(n.nodeType===3){if(r=e+n.textContent.length,e<=t&&r>=t)return{node:n,offset:t-e};e=r}e:{for(;n;){if(n.nextSibling){n=n.nextSibling;break e}n=n.parentNode}n=void 0}n=rs(n)}}function Cd(e,t){return e&&t?e===t?!0:e&&e.nodeType===3?!1:t&&t.nodeType===3?Cd(e,t.parentNode):("contains"in e)?e.contains(t):e.compareDocumentPosition?!!(e.compareDocumentPosition(t)&16):!1:!1}function _d(){for(var e=window,t=bl();t instanceof e.HTMLIFrameElement;){try{var n=typeof t.contentWindow.location.href==="string"}catch(r){n=!1}if(n)e=t.contentWindow;else break;t=bl(e.document)}return t}function Fo(e){var t=e&&e.nodeName&&e.nodeName.toLowerCase();return t&&(t==="input"&&(e.type==="text"||e.type==="search"||e.type==="tel"||e.type==="url"||e.type==="password")||t==="textarea"||e.contentEditable==="true")}function u0(e){var t=_d(),n=e.focusedElem,r=e.selectionRange;if(t!==n&&n&&n.ownerDocument&&Cd(n.ownerDocument.documentElement,n)){if(r!==null&&Fo(n)){if(t=r.start,e=r.end,e===void 0&&(e=t),"selectionStart"in n)n.selectionStart=t,n.selectionEnd=Math.min(e,n.value.length);else if(e=(t=n.ownerDocument||document)&&t.defaultView||window,e.getSelection){e=e.getSelection();var l=n.textContent.length,a=Math.min(r.start,l);r=r.end===void 0?a:Math.min(r.end,l),!e.extend&&a>r&&(l=r,r=a,a=l),l=ls(n,a);var i=ls(n,r);l&&i&&(e.rangeCount!==1||e.anchorNode!==l.node||e.anchorOffset!==l.offset||e.focusNode!==i.node||e.focusOffset!==i.offset)&&(t=t.createRange(),t.setStart(l.node,l.offset),e.removeAllRanges(),a>r?(e.addRange(t),e.extend(i.node,i.offset)):(t.setEnd(i.node,i.offset),e.addRange(t)))}}t=[];for(e=n;e=e.parentNode;)e.nodeType===1&&t.push({element:e,left:e.scrollLeft,top:e.scrollTop});typeof n.focus==="function"&&n.focus();for(n=0;n<t.length;n++)e=t[n],e.element.scrollLeft=e.left,e.element.scrollTop=e.top}}function as(e,t,n){var r=n.window===n?n.document:n.nodeType===9?n:n.ownerDocument;Ki||fn==null||fn!==bl(r)||(r=fn,("selectionStart"in r)&&Fo(r)?r={start:r.selectionStart,end:r.selectionEnd}:(r=(r.ownerDocument&&r.ownerDocument.defaultView||window).getSelection(),r={anchorNode:r.anchorNode,anchorOffset:r.anchorOffset,focusNode:r.focusNode,focusOffset:r.focusOffset}),gr&&Mr(gr,r)||(gr=r,r=Ql(bi,"onSelect"),0<r.length&&(t=new _o("onSelect","select",null,t,n),e.push({event:t,listeners:r}),t.target=fn)))}function wl(e,t){var n={};return n[e.toLowerCase()]=t.toLowerCase(),n["Webkit"+e]="webkit"+t,n["Moz"+e]="moz"+t,n}function fa(e){if(oi[e])return oi[e];if(!pn[e])return e;var t=pn[e],n;for(n in t)if(t.hasOwnProperty(n)&&n in Td)return oi[e]=t[n];return e}function Tt(e,t){Ad.set(e,t),jt(t,[e])}function os(e,t,n){var r=e.type||"unknown-event";e.currentTarget=n,dm(r,t,void 0,e),e.currentTarget=null}function Rd(e,t){t=(t&4)!==0;for(var n=0;n<e.length;n++){var r=e[n],l=r.event;r=r.listeners;e:{var a=void 0;if(t)for(var i=r.length-1;0<=i;i--){var o=r[i],u=o.instance,f=o.currentTarget;if(o=o.listener,u!==a&&l.isPropagationStopped())break e;os(l,o,f),a=u}else for(i=0;i<r.length;i++){if(o=r[i],u=o.instance,f=o.currentTarget,o=o.listener,u!==a&&l.isPropagationStopped())break e;os(l,o,f),a=u}}}if(Bl)throw e=Oi,Bl=!1,Oi=null,e}function U(e,t){var n=t[Yi];n===void 0&&(n=t[Yi]=new Set);var r=e+"__bubble";n.has(r)||(Od(t,e,2,!1),n.add(r))}function ui(e,t,n){var r=0;t&&(r|=4),Od(n,e,r,t)}function Fr(e){if(!e[Nl]){e[Nl]=!0,$s.forEach(function(n){n!=="selectionchange"&&(d0.has(n)||ui(n,!1,e),ui(n,!0,e))});var t=e.nodeType===9?e:e.ownerDocument;t===null||t[Nl]||(t[Nl]=!0,ui("selectionchange",!1,t))}}function Od(e,t,n,r){switch(yd(t)){case 1:var l=Cm;break;case 4:l=_m;break;default:l=zo}n=l.bind(null,t,n,e),l=void 0,!Ri||t!=="touchstart"&&t!=="touchmove"&&t!=="wheel"||(l=!0),r?l!==void 0?e.addEventListener(t,n,{capture:!0,passive:l}):e.addEventListener(t,n,!0):l!==void 0?e.addEventListener(t,n,{passive:l}):e.addEventListener(t,n,!1)}function si(e,t,n,r,l){var a=r;if((t&1)===0&&(t&2)===0&&r!==null)e:for(;;){if(r===null)return;var i=r.tag;if(i===3||i===4){var o=r.stateNode.containerInfo;if(o===l||o.nodeType===8&&o.parentNode===l)break;if(i===4)for(i=r.return;i!==null;){var u=i.tag;if(u===3||u===4){if(u=i.stateNode.containerInfo,u===l||u.nodeType===8&&u.parentNode===l)return}i=i.return}for(;o!==null;){if(i=Ht(o),i===null)return;if(u=i.tag,u===5||u===6){r=a=i;continue e}o=o.parentNode}}r=r.return}ld(function(){var f=a,h=No(n),g=[];e:{var v=Ad.get(e);if(v!==void 0){var S=_o,N=e;switch(e){case"keypress":if(Fl(n)===0)break e;case"keydown":case"keyup":S=$m;break;case"focusin":N="focus",S=ii;break;case"focusout":N="blur",S=ii;break;case"beforeblur":case"afterblur":S=ii;break;case"click":if(n.button===2)break e;case"auxclick":case"dblclick":case"mousedown":case"mousemove":case"mouseup":case"mouseout":case"mouseover":case"contextmenu":S=Gu;break;case"drag":case"dragend":case"dragenter":case"dragexit":case"dragleave":case"dragover":case"dragstart":case"drop":S=Fm;break;case"touchcancel":case"touchend":case"touchmove":case"touchstart":S=Vm;break;case Md:case Fd:case Pd:S=Am;break;case Id:S=Ym;break;case"scroll":S=Tm;break;case"wheel":S=Zm;break;case"copy":case"cut":case"paste":S=Om;break;case"gotpointercapture":case"lostpointercapture":case"pointercancel":case"pointerdown":case"pointermove":case"pointerout":case"pointerover":case"pointerup":S=qu}var x=(t&4)!==0,R=!x&&e==="scroll",p=x?v!==null?v+"Capture":null:v;x=[];for(var c=f,m;c!==null;){m=c;var k=m.stateNode;if(m.tag===5&&k!==null&&(m=k,p!==null&&(k=Er(c,p),k!=null&&x.push(Pr(c,k,m)))),R)break;c=c.return}0<x.length&&(v=new S(v,N,null,n,h),g.push({event:v,listeners:x}))}}if((t&7)===0){e:{if(v=e==="mouseover"||e==="pointerover",S=e==="mouseout"||e==="pointerout",v&&n!==Ii&&(N=n.relatedTarget||n.fromElement)&&(Ht(N)||N[lt]))break e;if(S||v){if(v=h.window===h?h:(v=h.ownerDocument)?v.defaultView||v.parentWindow:window,S){if(N=n.relatedTarget||n.toElement,S=f,N=N?Ht(N):null,N!==null&&(R=en(N),N!==R||N.tag!==5&&N.tag!==6))N=null}else S=null,N=f;if(S!==N){if(x=Gu,k="onMouseLeave",p="onMouseEnter",c="mouse",e==="pointerout"||e==="pointerover")x=qu,k="onPointerLeave",p="onPointerEnter",c="pointer";if(R=S==null?v:mn(S),m=N==null?v:mn(N),v=new x(k,c+"leave",S,n,h),v.target=R,v.relatedTarget=m,k=null,Ht(h)===f&&(x=new x(p,c+"enter",N,n,h),x.target=m,x.relatedTarget=R,k=x),R=k,S&&N)t:{x=S,p=N,c=0;for(m=x;m;m=on(m))c++;m=0;for(k=p;k;k=on(k))m++;for(;0<c-m;)x=on(x),c--;for(;0<m-c;)p=on(p),m--;for(;c--;){if(x===p||p!==null&&x===p.alternate)break t;x=on(x),p=on(p)}x=null}else x=null;S!==null&&us(g,v,S,x,!1),N!==null&&R!==null&&us(g,R,N,x,!0)}}}e:{if(v=f?mn(f):window,S=v.nodeName&&v.nodeName.toLowerCase(),S==="select"||S==="input"&&v.type==="file")var z=n0;else if(ts(v))if(Ed)z=i0;else{z=l0;var C=r0}else(S=v.nodeName)&&S.toLowerCase()==="input"&&(v.type==="checkbox"||v.type==="radio")&&(z=a0);if(z&&(z=z(e,f))){xd(g,z,n,h);break e}C&&C(e,v,f),e==="focusout"&&(C=v._wrapperState)&&C.controlled&&v.type==="number"&&_i(v,"number",v.value)}switch(C=f?mn(f):window,e){case"focusin":if(ts(C)||C.contentEditable==="true")fn=C,bi=f,gr=null;break;case"focusout":gr=bi=fn=null;break;case"mousedown":Ki=!0;break;case"contextmenu":case"mouseup":case"dragend":Ki=!1,as(g,n,h);break;case"selectionchange":if(s0)break;case"keydown":case"keyup":as(g,n,h)}var _;if(Mo)e:{switch(e){case"compositionstart":var T="onCompositionStart";break e;case"compositionend":T="onCompositionEnd";break e;case"compositionupdate":T="onCompositionUpdate";break e}T=void 0}else cn?Nd(e,n)&&(T="onCompositionEnd"):e==="keydown"&&n.keyCode===229&&(T="onCompositionStart");if(T&&(wd&&n.locale!=="ko"&&(cn||T!=="onCompositionStart"?T==="onCompositionEnd"&&cn&&(_=kd()):(vt=h,Co=("value"in vt)?vt.value:vt.textContent,cn=!0)),C=Ql(f,T),0<C.length&&(T=new Xu(T,e,null,n,h),g.push({event:T,listeners:C}),_?T.data=_:(_=Sd(n),_!==null&&(T.data=_)))),_=Xm?qm(e,n):jm(e,n))f=Ql(f,"onBeforeInput"),0<f.length&&(h=new Xu("onBeforeInput","beforeinput",null,n,h),g.push({event:h,listeners:f}),h.data=_)}Rd(g,t)})}function Pr(e,t,n){return{instance:e,listener:t,currentTarget:n}}function Ql(e,t){for(var n=t+"Capture",r=[];e!==null;){var l=e,a=l.stateNode;l.tag===5&&a!==null&&(l=a,a=Er(e,n),a!=null&&r.unshift(Pr(e,a,l)),a=Er(e,t),a!=null&&r.push(Pr(e,a,l))),e=e.return}return r}function on(e){if(e===null)return null;do e=e.return;while(e&&e.tag!==5);return e?e:null}function us(e,t,n,r,l){for(var a=t._reactName,i=[];n!==null&&n!==r;){var o=n,u=o.alternate,f=o.stateNode;if(u!==null&&u===r)break;o.tag===5&&f!==null&&(o=f,l?(u=Er(n,a),u!=null&&i.unshift(Pr(n,u,o))):l||(u=Er(n,a),u!=null&&i.push(Pr(n,u,o)))),n=n.return}i.length!==0&&e.push({event:t,listeners:i})}function ss(e){return(typeof e==="string"?e:""+e).replace(c0,`
`).replace(f0,"")}function Sl(e,t,n){if(t=ss(t),ss(e)!==t&&n)throw Error(w(425))}function Yl(){}function Vi(e,t){return e==="textarea"||e==="noscript"||typeof t.children==="string"||typeof t.children==="number"||typeof t.dangerouslySetInnerHTML==="object"&&t.dangerouslySetInnerHTML!==null&&t.dangerouslySetInnerHTML.__html!=null}function h0(e){setTimeout(function(){throw e})}function di(e,t){var n=t,r=0;do{var l=n.nextSibling;if(e.removeChild(n),l&&l.nodeType===8)if(n=l.data,n==="/$"){if(r===0){e.removeChild(l),_r(t);return}r--}else n!=="$"&&n!=="$?"&&n!=="$!"||r++;n=l}while(n);_r(t)}function Nt(e){for(;e!=null;e=e.nextSibling){var t=e.nodeType;if(t===1||t===3)break;if(t===8){if(t=e.data,t==="$"||t==="$!"||t==="$?")break;if(t==="/$")return null}}return e}function cs(e){e=e.previousSibling;for(var t=0;e;){if(e.nodeType===8){var n=e.data;if(n==="$"||n==="$!"||n==="$?"){if(t===0)return e;t--}else n==="/$"&&t++}e=e.previousSibling}return null}function Ht(e){var t=e[Je];if(t)return t;for(var n=e.parentNode;n;){if(t=n[lt]||n[Je]){if(n=t.alternate,t.child!==null||n!==null&&n.child!==null)for(e=cs(e);e!==null;){if(n=e[Je])return n;e=cs(e)}return t}e=n,n=e.parentNode}return null}function Br(e){return e=e[Je]||e[lt],!e||e.tag!==5&&e.tag!==6&&e.tag!==13&&e.tag!==3?null:e}function mn(e){if(e.tag===5||e.tag===6)return e.stateNode;throw Error(w(33))}function pa(e){return e[Ir]||null}function Mt(e){return{current:e}}function L(e){0>hn||(e.current=Ji[hn],Ji[hn]=null,hn--)}function D(e,t){hn++,Ji[hn]=e.current,e.current=t}function Tn(e,t){var n=e.type.contextTypes;if(!n)return _t;var r=e.stateNode;if(r&&r.__reactInternalMemoizedUnmaskedChildContext===t)return r.__reactInternalMemoizedMaskedChildContext;var l={},a;for(a in n)l[a]=t[a];return r&&(e=e.stateNode,e.__reactInternalMemoizedUnmaskedChildContext=t,e.__reactInternalMemoizedMaskedChildContext=l),l}function ke(e){return e=e.childContextTypes,e!==null&&e!==void 0}function Jl(){L(ye),L(ue)}function fs(e,t,n){if(ue.current!==_t)throw Error(w(168));D(ue,t),D(ye,n)}function Dd(e,t,n){var r=e.stateNode;if(t=t.childContextTypes,typeof r.getChildContext!=="function")return n;r=r.getChildContext();for(var l in r)if(!(l in t))throw Error(w(108,rm(e)||"Unknown",l));return V({},n,r)}function Zl(e){return e=(e=e.stateNode)&&e.__reactInternalMemoizedMergedChildContext||_t,Jt=ue.current,D(ue,e),D(ye,ye.current),!0}function ps(e,t,n){var r=e.stateNode;if(!r)throw Error(w(169));n?(e=Dd(e,t,Jt),r.__reactInternalMemoizedMergedChildContext=e,L(ye),L(ue),D(ue,e)):L(ye),D(ye,n)}function Ud(e){je===null?je=[e]:je.push(e)}function y0(e){ma=!0,Ud(e)}function Ft(){if(!ci&&je!==null){ci=!0;var e=0,t=O;try{var n=je;for(O=1;e<n.length;e++){var r=n[e];do r=r(!0);while(r!==null)}je=null,ma=!1}catch(l){throw je!==null&&(je=je.slice(e+1)),ud(So,Ft),l}finally{O=t,ci=!1}}return null}function Bt(e,t){vn[gn++]=Xl,vn[gn++]=Gl,Gl=e,Xl=t}function Ld(e,t,n){Me[Fe++]=et,Me[Fe++]=tt,Me[Fe++]=Zt,Zt=e;var r=et;e=tt;var l=32-Be(r)-1;r&=~(1<<l),n+=1;var a=32-Be(t)+l;if(30<a){var i=l-l%5;a=(r&(1<<i)-1).toString(32),r>>=i,l-=i,et=1<<32-Be(t)+l|n<<l|r,tt=a+e}else et=1<<a|n<<l|r,tt=e}function Po(e){e.return!==null&&(Bt(e,1),Ld(e,1,0))}function Io(e){for(;e===Gl;)Gl=vn[--gn],vn[gn]=null,Xl=vn[--gn],vn[gn]=null;for(;e===Zt;)Zt=Me[--Fe],Me[Fe]=null,tt=Me[--Fe],Me[Fe]=null,et=Me[--Fe],Me[Fe]=null}function bd(e,t){var n=Pe(5,null,null,0);n.elementType="DELETED",n.stateNode=t,n.return=e,t=e.deletions,t===null?(e.deletions=[n],e.flags|=16):t.push(n)}function ms(e,t){switch(e.tag){case 5:var n=e.type;return t=t.nodeType!==1||n.toLowerCase()!==t.nodeName.toLowerCase()?null:t,t!==null?(e.stateNode=t,ze=e,Ee=Nt(t.firstChild),!0):!1;case 6:return t=e.pendingProps===""||t.nodeType!==3?null:t,t!==null?(e.stateNode=t,ze=e,Ee=null,!0):!1;case 13:return t=t.nodeType!==8?null:t,t!==null?(n=Zt!==null?{id:et,overflow:tt}:null,e.memoizedState={dehydrated:t,treeContext:n,retryLane:1073741824},n=Pe(18,null,null,0),n.stateNode=t,n.return=e,e.child=n,ze=e,Ee=null,!0):!1;default:return!1}}function Zi(e){return(e.mode&1)!==0&&(e.flags&128)===0}function Gi(e){if(b){var t=Ee;if(t){var n=t;if(!ms(e,t)){if(Zi(e))throw Error(w(418));t=Nt(n.nextSibling);var r=ze;t&&ms(e,t)?bd(r,n):(e.flags=e.flags&-4097|2,b=!1,ze=e)}}else{if(Zi(e))throw Error(w(418));e.flags=e.flags&-4097|2,b=!1,ze=e}}}function hs(e){for(e=e.return;e!==null&&e.tag!==5&&e.tag!==3&&e.tag!==13;)e=e.return;ze=e}function xl(e){if(e!==ze)return!1;if(!b)return hs(e),b=!0,!1;var t;if((t=e.tag!==3)&&!(t=e.tag!==5)&&(t=e.type,t=t!=="head"&&t!=="body"&&!Vi(e.type,e.memoizedProps)),t&&(t=Ee)){if(Zi(e))throw Kd(),Error(w(418));for(;t;)bd(e,t),t=Nt(t.nextSibling)}if(hs(e),e.tag===13){if(e=e.memoizedState,e=e!==null?e.dehydrated:null,!e)throw Error(w(317));e:{e=e.nextSibling;for(t=0;e;){if(e.nodeType===8){var n=e.data;if(n==="/$"){if(t===0){Ee=Nt(e.nextSibling);break e}t--}else n!=="$"&&n!=="$!"&&n!=="$?"||t++}e=e.nextSibling}Ee=null}}else Ee=ze?Nt(e.stateNode.nextSibling):null;return!0}function Kd(){for(var e=Ee;e;)e=Nt(e.nextSibling)}function Mn(){Ee=ze=null,b=!1}function Ao(e){Ke===null?Ke=[e]:Ke.push(e)}function nr(e,t,n){if(e=n.ref,e!==null&&typeof e!=="function"&&typeof e!=="object"){if(n._owner){if(n=n._owner,n){if(n.tag!==1)throw Error(w(309));var r=n.stateNode}if(!r)throw Error(w(147,e));var l=r,a=""+e;if(t!==null&&t.ref!==null&&typeof t.ref==="function"&&t.ref._stringRef===a)return t.ref;return t=function(i){var o=l.refs;i===null?delete o[a]:o[a]=i},t._stringRef=a,t}if(typeof e!=="string")throw Error(w(284));if(!n._owner)throw Error(w(290,e))}return e}function El(e,t){throw e=Object.prototype.toString.call(t),Error(w(31,e==="[object Object]"?"object with keys {"+Object.keys(t).join(", ")+"}":e))}function vs(e){var t=e._init;return t(e._payload)}function Bd(e){function t(p,c){if(e){var m=p.deletions;m===null?(p.deletions=[c],p.flags|=16):m.push(c)}}function n(p,c){if(!e)return null;for(;c!==null;)t(p,c),c=c.sibling;return null}function r(p,c){for(p=new Map;c!==null;)c.key!==null?p.set(c.key,c):p.set(c.index,c),c=c.sibling;return p}function l(p,c){return p=zt(p,c),p.index=0,p.sibling=null,p}function a(p,c,m){if(p.index=m,!e)return p.flags|=1048576,c;if(m=p.alternate,m!==null)return m=m.index,m<c?(p.flags|=2,c):m;return p.flags|=2,c}function i(p){return e&&p.alternate===null&&(p.flags|=2),p}function o(p,c,m,k){if(c===null||c.tag!==6)return c=yi(m,p.mode,k),c.return=p,c;return c=l(c,m),c.return=p,c}function u(p,c,m,k){var z=m.type;if(z===dn)return h(p,c,m.props.children,k,m.key);if(c!==null&&(c.elementType===z||typeof z==="object"&&z!==null&&z.$$typeof===ft&&vs(z)===c.type))return k=l(c,m.props),k.ref=nr(p,c,m),k.return=p,k;return k=Ll(m.type,m.key,m.props,null,p.mode,k),k.ref=nr(p,c,m),k.return=p,k}function f(p,c,m,k){if(c===null||c.tag!==4||c.stateNode.containerInfo!==m.containerInfo||c.stateNode.implementation!==m.implementation)return c=ki(m,p.mode,k),c.return=p,c;return c=l(c,m.children||[]),c.return=p,c}function h(p,c,m,k,z){if(c===null||c.tag!==7)return c=Yt(m,p.mode,k,z),c.return=p,c;return c=l(c,m),c.return=p,c}function g(p,c,m){if(typeof c==="string"&&c!==""||typeof c==="number")return c=yi(""+c,p.mode,m),c.return=p,c;if(typeof c==="object"&&c!==null){switch(c.$$typeof){case pl:return m=Ll(c.type,c.key,c.props,null,p.mode,m),m.ref=nr(p,null,c),m.return=p,m;case sn:return c=ki(c,p.mode,m),c.return=p,c;case ft:var k=c._init;return g(p,k(c._payload),m)}if(ir(c)||qn(c))return c=Yt(c,p.mode,m,null),c.return=p,c;El(p,c)}return null}function v(p,c,m,k){var z=c!==null?c.key:null;if(typeof m==="string"&&m!==""||typeof m==="number")return z!==null?null:o(p,c,""+m,k);if(typeof m==="object"&&m!==null){switch(m.$$typeof){case pl:return m.key===z?u(p,c,m,k):null;case sn:return m.key===z?f(p,c,m,k):null;case ft:return z=m._init,v(p,c,z(m._payload),k)}if(ir(m)||qn(m))return z!==null?null:h(p,c,m,k,null);El(p,m)}return null}function S(p,c,m,k,z){if(typeof k==="string"&&k!==""||typeof k==="number")return p=p.get(m)||null,o(c,p,""+k,z);if(typeof k==="object"&&k!==null){switch(k.$$typeof){case pl:return p=p.get(k.key===null?m:k.key)||null,u(c,p,k,z);case sn:return p=p.get(k.key===null?m:k.key)||null,f(c,p,k,z);case ft:var C=k._init;return S(p,c,m,C(k._payload),z)}if(ir(k)||qn(k))return p=p.get(m)||null,h(c,p,k,z,null);El(c,k)}return null}function N(p,c,m,k){for(var z=null,C=null,_=c,T=c=0,B=null;_!==null&&T<m.length;T++){_.index>T?(B=_,_=null):B=_.sibling;var M=v(p,_,m[T],k);if(M===null){_===null&&(_=B);break}e&&_&&M.alternate===null&&t(p,_),c=a(M,c,T),C===null?z=M:C.sibling=M,C=M,_=B}if(T===m.length)return n(p,_),b&&Bt(p,T),z;if(_===null){for(;T<m.length;T++)_=g(p,m[T],k),_!==null&&(c=a(_,c,T),C===null?z=_:C.sibling=_,C=_);return b&&Bt(p,T),z}for(_=r(p,_);T<m.length;T++)B=S(_,p,T,m[T],k),B!==null&&(e&&B.alternate!==null&&_.delete(B.key===null?T:B.key),c=a(B,c,T),C===null?z=B:C.sibling=B,C=B);return e&&_.forEach(function(Ne){return t(p,Ne)}),b&&Bt(p,T),z}function x(p,c,m,k){var z=qn(m);if(typeof z!=="function")throw Error(w(150));if(m=z.call(m),m==null)throw Error(w(151));for(var C=z=null,_=c,T=c=0,B=null,M=m.next();_!==null&&!M.done;T++,M=m.next()){_.index>T?(B=_,_=null):B=_.sibling;var Ne=v(p,_,M.value,k);if(Ne===null){_===null&&(_=B);break}e&&_&&Ne.alternate===null&&t(p,_),c=a(Ne,c,T),C===null?z=Ne:C.sibling=Ne,C=Ne,_=B}if(M.done)return n(p,_),b&&Bt(p,T),z;if(_===null){for(;!M.done;T++,M=m.next())M=g(p,M.value,k),M!==null&&(c=a(M,c,T),C===null?z=M:C.sibling=M,C=M);return b&&Bt(p,T),z}for(_=r(p,_);!M.done;T++,M=m.next())M=S(_,p,T,M.value,k),M!==null&&(e&&M.alternate!==null&&_.delete(M.key===null?T:M.key),c=a(M,c,T),C===null?z=M:C.sibling=M,C=M);return e&&_.forEach(function(Kn){return t(p,Kn)}),b&&Bt(p,T),z}function R(p,c,m,k){if(typeof m==="object"&&m!==null&&m.type===dn&&m.key===null&&(m=m.props.children),typeof m==="object"&&m!==null){switch(m.$$typeof){case pl:e:{for(var z=m.key,C=c;C!==null;){if(C.key===z){if(z=m.type,z===dn){if(C.tag===7){n(p,C.sibling),c=l(C,m.props.children),c.return=p,p=c;break e}}else if(C.elementType===z||typeof z==="object"&&z!==null&&z.$$typeof===ft&&vs(z)===C.type){n(p,C.sibling),c=l(C,m.props),c.ref=nr(p,C,m),c.return=p,p=c;break e}n(p,C);break}else t(p,C);C=C.sibling}m.type===dn?(c=Yt(m.props.children,p.mode,k,m.key),c.return=p,p=c):(k=Ll(m.type,m.key,m.props,null,p.mode,k),k.ref=nr(p,c,m),k.return=p,p=k)}return i(p);case sn:e:{for(C=m.key;c!==null;){if(c.key===C)if(c.tag===4&&c.stateNode.containerInfo===m.containerInfo&&c.stateNode.implementation===m.implementation){n(p,c.sibling),c=l(c,m.children||[]),c.return=p,p=c;break e}else{n(p,c);break}else t(p,c);c=c.sibling}c=ki(m,p.mode,k),c.return=p,p=c}return i(p);case ft:return C=m._init,R(p,c,C(m._payload),k)}if(ir(m))return N(p,c,m,k);if(qn(m))return x(p,c,m,k);El(p,m)}return typeof m==="string"&&m!==""||typeof m==="number"?(m=""+m,c!==null&&c.tag===6?(n(p,c.sibling),c=l(c,m),c.return=p,p=c):(n(p,c),c=yi(m,p.mode,k),c.return=p,p=c),i(p)):n(p,c)}return R}function Oo(){Ro=yn=jl=null}function Do(e){var t=ql.current;L(ql),e._currentValue=t}function Xi(e,t,n){for(;e!==null;){var r=e.alternate;if((e.childLanes&t)!==t?(e.childLanes|=t,r!==null&&(r.childLanes|=t)):r!==null&&(r.childLanes&t)!==t&&(r.childLanes|=t),e===n)break;e=e.return}}function zn(e,t){jl=e,Ro=yn=null,e=e.dependencies,e!==null&&e.firstContext!==null&&((e.lanes&t)!==0&&(ge=!0),e.firstContext=null)}function Ae(e){var t=e._currentValue;if(Ro!==e)if(e={context:e,memoizedValue:t,next:null},yn===null){if(jl===null)throw Error(w(308));yn=e,jl.dependencies={lanes:0,firstContext:e}}else yn=yn.next=e;return t}function Uo(e){Wt===null?Wt=[e]:Wt.push(e)}function Hd(e,t,n,r){var l=t.interleaved;return l===null?(n.next=n,Uo(t)):(n.next=l.next,l.next=n),t.interleaved=n,at(e,r)}function at(e,t){e.lanes|=t;var n=e.alternate;n!==null&&(n.lanes|=t),n=e;for(e=e.return;e!==null;)e.childLanes|=t,n=e.alternate,n!==null&&(n.childLanes|=t),n=e,e=e.return;return n.tag===3?n.stateNode:null}function Lo(e){e.updateQueue={baseState:e.memoizedState,firstBaseUpdate:null,lastBaseUpdate:null,shared:{pending:null,interleaved:null,lanes:0},effects:null}}function Wd(e,t){e=e.updateQueue,t.updateQueue===e&&(t.updateQueue={baseState:e.baseState,firstBaseUpdate:e.firstBaseUpdate,lastBaseUpdate:e.lastBaseUpdate,shared:e.shared,effects:e.effects})}function nt(e,t){return{eventTime:e,lane:t,tag:0,payload:null,callback:null,next:null}}function St(e,t,n){var r=e.updateQueue;if(r===null)return null;if(r=r.shared,(P&2)!==0){var l=r.pending;return l===null?t.next=t:(t.next=l.next,l.next=t),r.pending=t,at(e,n)}return l=r.interleaved,l===null?(t.next=t,Uo(r)):(t.next=l.next,l.next=t),r.interleaved=t,at(e,n)}function Il(e,t,n){if(t=t.updateQueue,t!==null&&(t=t.shared,(n&4194240)!==0)){var r=t.lanes;r&=e.pendingLanes,n|=r,t.lanes=n,xo(e,n)}}function gs(e,t){var{updateQueue:n,alternate:r}=e;if(r!==null&&(r=r.updateQueue,n===r)){var l=null,a=null;if(n=n.firstBaseUpdate,n!==null){do{var i={eventTime:n.eventTime,lane:n.lane,tag:n.tag,payload:n.payload,callback:n.callback,next:null};a===null?l=a=i:a=a.next=i,n=n.next}while(n!==null);a===null?l=a=t:a=a.next=t}else l=a=t;n={baseState:r.baseState,firstBaseUpdate:l,lastBaseUpdate:a,shared:r.shared,effects:r.effects},e.updateQueue=n;return}e=n.lastBaseUpdate,e===null?n.firstBaseUpdate=t:e.next=t,n.lastBaseUpdate=t}function ea(e,t,n,r){var l=e.updateQueue;pt=!1;var{firstBaseUpdate:a,lastBaseUpdate:i}=l,o=l.shared.pending;if(o!==null){l.shared.pending=null;var u=o,f=u.next;u.next=null,i===null?a=f:i.next=f,i=u;var h=e.alternate;h!==null&&(h=h.updateQueue,o=h.lastBaseUpdate,o!==i&&(o===null?h.firstBaseUpdate=f:o.next=f,h.lastBaseUpdate=u))}if(a!==null){var g=l.baseState;i=0,h=f=u=null,o=a;do{var{lane:v,eventTime:S}=o;if((r&v)===v){h!==null&&(h=h.next={eventTime:S,lane:0,tag:o.tag,payload:o.payload,callback:o.callback,next:null});e:{var N=e,x=o;switch(v=t,S=n,x.tag){case 1:if(N=x.payload,typeof N==="function"){g=N.call(S,g,v);break e}g=N;break e;case 3:N.flags=N.flags&-65537|128;case 0:if(N=x.payload,v=typeof N==="function"?N.call(S,g,v):N,v===null||v===void 0)break e;g=V({},g,v);break e;case 2:pt=!0}}o.callback!==null&&o.lane!==0&&(e.flags|=64,v=l.effects,v===null?l.effects=[o]:v.push(o))}else S={eventTime:S,lane:v,tag:o.tag,payload:o.payload,callback:o.callback,next:null},h===null?(f=h=S,u=g):h=h.next=S,i|=v;if(o=o.next,o===null)if(o=l.shared.pending,o===null)break;else v=o,o=v.next,v.next=null,l.lastBaseUpdate=v,l.shared.pending=null}while(1);if(h===null&&(u=g),l.baseState=u,l.firstBaseUpdate=f,l.lastBaseUpdate=h,t=l.shared.interleaved,t!==null){l=t;do i|=l.lane,l=l.next;while(l!==t)}else a===null&&(l.shared.lanes=0);Xt|=i,e.lanes=i,e.memoizedState=g}}function ys(e,t,n){if(e=t.effects,t.effects=null,e!==null)for(t=0;t<e.length;t++){var r=e[t],l=r.callback;if(l!==null){if(r.callback=null,r=n,typeof l!=="function")throw Error(w(191,l));l.call(r)}}}function Vt(e){if(e===$r)throw Error(w(174));return e}function bo(e,t){switch(D(Rr,t),D(Ar,e),D(Ge,$r),e=t.nodeType,e){case 9:case 11:t=(t=t.documentElement)?t.namespaceURI:Mi(null,"");break;default:e=e===8?t.parentNode:t,t=e.namespaceURI||null,e=e.tagName,t=Mi(t,e)}L(Ge),D(Ge,t)}function Pn(){L(Ge),L(Ar),L(Rr)}function Vd(e){Vt(Rr.current);var t=Vt(Ge.current),n=Mi(t,e.type);t!==n&&(D(Ar,e),D(Ge,n))}function Ko(e){Ar.current===e&&(L(Ge),L(Ar))}function ta(e){for(var t=e;t!==null;){if(t.tag===13){var n=t.memoizedState;if(n!==null&&(n=n.dehydrated,n===null||n.data==="$?"||n.data==="$!"))return t}else if(t.tag===19&&t.memoizedProps.revealOrder!==void 0){if((t.flags&128)!==0)return t}else if(t.child!==null){t.child.return=t,t=t.child;continue}if(t===e)break;for(;t.sibling===null;){if(t.return===null||t.return===e)return null;t=t.return}t.sibling.return=t.return,t=t.sibling}return null}function Bo(){for(var e=0;e<fi.length;e++)fi[e]._workInProgressVersionPrimary=null;fi.length=0}function ae(){throw Error(w(321))}function $o(e,t){if(t===null)return!1;for(var n=0;n<t.length&&n<e.length;n++)if(!He(e[n],t[n]))return!1;return!0}function Ho(e,t,n,r,l,a){if(Gt=a,W=t,t.memoizedState=null,t.updateQueue=null,t.lanes=0,Al.current=e===null||e.memoizedState===null?E0:z0,e=n(r,l),yr){a=0;do{if(yr=!1,Or=0,25<=a)throw Error(w(301));a+=1,j=G=null,t.updateQueue=null,Al.current=C0,e=n(r,l)}while(yr)}if(Al.current=ra,t=G!==null&&G.next!==null,Gt=0,j=G=W=null,na=!1,t)throw Error(w(300));return e}function Wo(){var e=Or!==0;return Or=0,e}function Ye(){var e={memoizedState:null,baseState:null,baseQueue:null,queue:null,next:null};return j===null?W.memoizedState=j=e:j=j.next=e,j}function Re(){if(G===null){var e=W.alternate;e=e!==null?e.memoizedState:null}else e=G.next;var t=j===null?W.memoizedState:j.next;if(t!==null)j=t,G=e;else{if(e===null)throw Error(w(310));G=e,e={memoizedState:G.memoizedState,baseState:G.baseState,baseQueue:G.baseQueue,queue:G.queue,next:null},j===null?W.memoizedState=j=e:j=j.next=e}return j}function Dr(e,t){return typeof t==="function"?t(e):t}function mi(e){var t=Re(),n=t.queue;if(n===null)throw Error(w(311));n.lastRenderedReducer=e;var r=G,l=r.baseQueue,a=n.pending;if(a!==null){if(l!==null){var i=l.next;l.next=a.next,a.next=i}r.baseQueue=l=a,n.pending=null}if(l!==null){a=l.next,r=r.baseState;var o=i=null,u=null,f=a;do{var h=f.lane;if((Gt&h)===h)u!==null&&(u=u.next={lane:0,action:f.action,hasEagerState:f.hasEagerState,eagerState:f.eagerState,next:null}),r=f.hasEagerState?f.eagerState:e(r,f.action);else{var g={lane:h,action:f.action,hasEagerState:f.hasEagerState,eagerState:f.eagerState,next:null};u===null?(o=u=g,i=r):u=u.next=g,W.lanes|=h,Xt|=h}f=f.next}while(f!==null&&f!==a);u===null?i=r:u.next=o,He(r,t.memoizedState)||(ge=!0),t.memoizedState=r,t.baseState=i,t.baseQueue=u,n.lastRenderedState=r}if(e=n.interleaved,e!==null){l=e;do a=l.lane,W.lanes|=a,Xt|=a,l=l.next;while(l!==e)}else l===null&&(n.lanes=0);return[t.memoizedState,n.dispatch]}function hi(e){var t=Re(),n=t.queue;if(n===null)throw Error(w(311));n.lastRenderedReducer=e;var{dispatch:r,pending:l}=n,a=t.memoizedState;if(l!==null){n.pending=null;var i=l=l.next;do a=e(a,i.action),i=i.next;while(i!==l);He(a,t.memoizedState)||(ge=!0),t.memoizedState=a,t.baseQueue===null&&(t.baseState=a),n.lastRenderedState=a}return[a,r]}function Qd(){}function Yd(e,t){var n=W,r=Re(),l=t(),a=!He(r.memoizedState,l);if(a&&(r.memoizedState=l,ge=!0),r=r.queue,Vo(Gd.bind(null,n,r,e),[e]),r.getSnapshot!==t||a||j!==null&&j.memoizedState.tag&1){if(n.flags|=2048,Ur(9,Zd.bind(null,n,r,l,t),void 0,null),ee===null)throw Error(w(349));(Gt&30)!==0||Jd(n,t,l)}return l}function Jd(e,t,n){e.flags|=16384,e={getSnapshot:t,value:n},t=W.updateQueue,t===null?(t={lastEffect:null,stores:null},W.updateQueue=t,t.stores=[e]):(n=t.stores,n===null?t.stores=[e]:n.push(e))}function Zd(e,t,n,r){t.value=n,t.getSnapshot=r,Xd(t)&&qd(e)}function Gd(e,t,n){return n(function(){Xd(t)&&qd(e)})}function Xd(e){var t=e.getSnapshot;e=e.value;try{var n=t();return!He(e,n)}catch(r){return!0}}function qd(e){var t=at(e,1);t!==null&&$e(t,e,1,-1)}function ks(e){var t=Ye();return typeof e==="function"&&(e=e()),t.memoizedState=t.baseState=e,e={pending:null,interleaved:null,lanes:0,dispatch:null,lastRenderedReducer:Dr,lastRenderedState:e},t.queue=e,e=e.dispatch=x0.bind(null,W,e),[t.memoizedState,e]}function Ur(e,t,n,r){return e={tag:e,create:t,destroy:n,deps:r,next:null},t=W.updateQueue,t===null?(t={lastEffect:null,stores:null},W.updateQueue=t,t.lastEffect=e.next=e):(n=t.lastEffect,n===null?t.lastEffect=e.next=e:(r=n.next,n.next=e,e.next=r,t.lastEffect=e)),e}function jd(){return Re().memoizedState}function Rl(e,t,n,r){var l=Ye();W.flags|=e,l.memoizedState=Ur(1|t,n,void 0,r===void 0?null:r)}function ha(e,t,n,r){var l=Re();r=r===void 0?null:r;var a=void 0;if(G!==null){var i=G.memoizedState;if(a=i.destroy,r!==null&&$o(r,i.deps)){l.memoizedState=Ur(t,n,a,r);return}}W.flags|=e,l.memoizedState=Ur(1|t,n,a,r)}function ws(e,t){return Rl(8390656,8,e,t)}function Vo(e,t){return ha(2048,8,e,t)}function ec(e,t){return ha(4,2,e,t)}function tc(e,t){return ha(4,4,e,t)}function nc(e,t){if(typeof t==="function")return e=e(),t(e),function(){t(null)};if(t!==null&&t!==void 0)return e=e(),t.current=e,function(){t.current=null}}function rc(e,t,n){return n=n!==null&&n!==void 0?n.concat([e]):null,ha(4,4,nc.bind(null,t,e),n)}function Qo(){}function lc(e,t){var n=Re();t=t===void 0?null:t;var r=n.memoizedState;if(r!==null&&t!==null&&$o(t,r[1]))return r[0];return n.memoizedState=[e,t],e}function ac(e,t){var n=Re();t=t===void 0?null:t;var r=n.memoizedState;if(r!==null&&t!==null&&$o(t,r[1]))return r[0];return e=e(),n.memoizedState=[e,t],e}function ic(e,t,n){if((Gt&21)===0)return e.baseState&&(e.baseState=!1,ge=!0),e.memoizedState=n;return He(n,t)||(n=cd(),W.lanes|=n,Xt|=n,e.baseState=!0),t}function N0(e,t){var n=O;O=n!==0&&4>n?n:4,e(!0);var r=pi.transition;pi.transition={};try{e(!1),t()}finally{O=n,pi.transition=r}}function oc(){return Re().memoizedState}function S0(e,t,n){var r=Et(e);if(n={lane:r,action:n,hasEagerState:!1,eagerState:null,next:null},uc(e))sc(t,n);else if(n=Hd(e,t,n,r),n!==null){var l=ce();$e(n,e,r,l),dc(n,t,r)}}function x0(e,t,n){var r=Et(e),l={lane:r,action:n,hasEagerState:!1,eagerState:null,next:null};if(uc(e))sc(t,l);else{var a=e.alternate;if(e.lanes===0&&(a===null||a.lanes===0)&&(a=t.lastRenderedReducer,a!==null))try{var i=t.lastRenderedState,o=a(i,n);if(l.hasEagerState=!0,l.eagerState=o,He(o,i)){var u=t.interleaved;u===null?(l.next=l,Uo(t)):(l.next=u.next,u.next=l),t.interleaved=l;return}}catch(f){}finally{}n=Hd(e,t,l,r),n!==null&&(l=ce(),$e(n,e,r,l),dc(n,t,r))}}function uc(e){var t=e.alternate;return e===W||t!==null&&t===W}function sc(e,t){yr=na=!0;var n=e.pending;n===null?t.next=t:(t.next=n.next,n.next=t),e.pending=t}function dc(e,t,n){if((n&4194240)!==0){var r=t.lanes;r&=e.pendingLanes,n|=r,t.lanes=n,xo(e,n)}}function Le(e,t){if(e&&e.defaultProps){t=V({},t),e=e.defaultProps;for(var n in e)t[n]===void 0&&(t[n]=e[n]);return t}return t}function qi(e,t,n,r){t=e.memoizedState,n=n(r,t),n=n===null||n===void 0?t:V({},t,n),e.memoizedState=n,e.lanes===0&&(e.updateQueue.baseState=n)}function Ns(e,t,n,r,l,a,i){return e=e.stateNode,typeof e.shouldComponentUpdate==="function"?e.shouldComponentUpdate(r,a,i):t.prototype&&t.prototype.isPureReactComponent?!Mr(n,r)||!Mr(l,a):!0}function cc(e,t,n){var r=!1,l=_t,a=t.contextType;return typeof a==="object"&&a!==null?a=Ae(a):(l=ke(t)?Jt:ue.current,r=t.contextTypes,a=(r=r!==null&&r!==void 0)?Tn(e,l):_t),t=new t(n,a),e.memoizedState=t.state!==null&&t.state!==void 0?t.state:null,t.updater=va,e.stateNode=t,t._reactInternals=e,r&&(e=e.stateNode,e.__reactInternalMemoizedUnmaskedChildContext=l,e.__reactInternalMemoizedMaskedChildContext=a),t}function Ss(e,t,n,r){e=t.state,typeof t.componentWillReceiveProps==="function"&&t.componentWillReceiveProps(n,r),typeof t.UNSAFE_componentWillReceiveProps==="function"&&t.UNSAFE_componentWillReceiveProps(n,r),t.state!==e&&va.enqueueReplaceState(t,t.state,null)}function ji(e,t,n,r){var l=e.stateNode;l.props=n,l.state=e.memoizedState,l.refs={},Lo(e);var a=t.contextType;typeof a==="object"&&a!==null?l.context=Ae(a):(a=ke(t)?Jt:ue.current,l.context=Tn(e,a)),l.state=e.memoizedState,a=t.getDerivedStateFromProps,typeof a==="function"&&(qi(e,t,a,n),l.state=e.memoizedState),typeof t.getDerivedStateFromProps==="function"||typeof l.getSnapshotBeforeUpdate==="function"||typeof l.UNSAFE_componentWillMount!=="function"&&typeof l.componentWillMount!=="function"||(t=l.state,typeof l.componentWillMount==="function"&&l.componentWillMount(),typeof l.UNSAFE_componentWillMount==="function"&&l.UNSAFE_componentWillMount(),t!==l.state&&va.enqueueReplaceState(l,l.state,null),ea(e,n,l,r),l.state=e.memoizedState),typeof l.componentDidMount==="function"&&(e.flags|=4194308)}function In(e,t){try{var n="",r=t;do n+=nm(r),r=r.return;while(r);var l=n}catch(a){l=`
Error generating stack: `+a.message+`
`+a.stack}return{value:e,source:t,stack:l,digest:null}}function vi(e,t,n){return{value:e,source:null,stack:n!=null?n:null,digest:t!=null?t:null}}function eo(e,t){try{console.error(t.value)}catch(n){setTimeout(function(){throw n})}}function fc(e,t,n){n=nt(-1,n),n.tag=3,n.payload={element:null};var r=t.value;return n.callback=function(){aa||(aa=!0,co=r),eo(e,t)},n}function pc(e,t,n){n=nt(-1,n),n.tag=3;var r=e.type.getDerivedStateFromError;if(typeof r==="function"){var l=t.value;n.payload=function(){return r(l)},n.callback=function(){eo(e,t)}}var a=e.stateNode;return a!==null&&typeof a.componentDidCatch==="function"&&(n.callback=function(){eo(e,t),typeof r!=="function"&&(xt===null?xt=new Set([this]):xt.add(this));var i=t.stack;this.componentDidCatch(t.value,{componentStack:i!==null?i:""})}),n}function xs(e,t,n){var r=e.pingCache;if(r===null){r=e.pingCache=new _0;var l=new Set;r.set(t,l)}else l=r.get(t),l===void 0&&(l=new Set,r.set(t,l));l.has(n)||(l.add(n),e=B0.bind(null,e,t,n),t.then(e,e))}function Es(e){do{var t;if(t=e.tag===13)t=e.memoizedState,t=t!==null?t.dehydrated!==null?!0:!1:!0;if(t)return e;e=e.return}while(e!==null);return null}function zs(e,t,n,r,l){if((e.mode&1)===0)return e===t?e.flags|=65536:(e.flags|=128,n.flags|=131072,n.flags&=-52805,n.tag===1&&(n.alternate===null?n.tag=17:(t=nt(-1,1),t.tag=2,St(n,t,1))),n.lanes|=1),e;return e.flags|=65536,e.lanes=l,e}function de(e,t,n,r){t.child=e===null?$d(t,null,n,r):Fn(t,e.child,n,r)}function Cs(e,t,n,r,l){n=n.render;var a=t.ref;if(zn(t,l),r=Ho(e,t,n,r,a,l),n=Wo(),e!==null&&!ge)return t.updateQueue=e.updateQueue,t.flags&=-2053,e.lanes&=~l,it(e,t,l);return b&&n&&Po(t),t.flags|=1,de(e,t,r,l),t.child}function _s(e,t,n,r,l){if(e===null){var a=n.type;if(typeof a==="function"&&!eu(a)&&a.defaultProps===void 0&&n.compare===null&&n.defaultProps===void 0)return t.tag=15,t.type=a,mc(e,t,a,r,l);return e=Ll(n.type,null,r,t,t.mode,l),e.ref=t.ref,e.return=t,t.child=e}if(a=e.child,(e.lanes&l)===0){var i=a.memoizedProps;if(n=n.compare,n=n!==null?n:Mr,n(i,r)&&e.ref===t.ref)return it(e,t,l)}return t.flags|=1,e=zt(a,r),e.ref=t.ref,e.return=t,t.child=e}function mc(e,t,n,r,l){if(e!==null){var a=e.memoizedProps;if(Mr(a,r)&&e.ref===t.ref)if(ge=!1,t.pendingProps=r=a,(e.lanes&l)!==0)(e.flags&131072)!==0&&(ge=!0);else return t.lanes=e.lanes,it(e,t,l)}return to(e,t,n,r,l)}function hc(e,t,n){var r=t.pendingProps,l=r.children,a=e!==null?e.memoizedState:null;if(r.mode==="hidden")if((t.mode&1)===0)t.memoizedState={baseLanes:0,cachePool:null,transitions:null},D(wn,xe),xe|=n;else{if((n&1073741824)===0)return e=a!==null?a.baseLanes|n:n,t.lanes=t.childLanes=1073741824,t.memoizedState={baseLanes:e,cachePool:null,transitions:null},t.updateQueue=null,D(wn,xe),xe|=e,null;t.memoizedState={baseLanes:0,cachePool:null,transitions:null},r=a!==null?a.baseLanes:n,D(wn,xe),xe|=r}else a!==null?(r=a.baseLanes|n,t.memoizedState=null):r=n,D(wn,xe),xe|=r;return de(e,t,l,n),t.child}function vc(e,t){var n=t.ref;if(e===null&&n!==null||e!==null&&e.ref!==n)t.flags|=512,t.flags|=2097152}function to(e,t,n,r,l){var a=ke(n)?Jt:ue.current;if(a=Tn(t,a),zn(t,l),n=Ho(e,t,n,r,a,l),r=Wo(),e!==null&&!ge)return t.updateQueue=e.updateQueue,t.flags&=-2053,e.lanes&=~l,it(e,t,l);return b&&r&&Po(t),t.flags|=1,de(e,t,n,l),t.child}function Ts(e,t,n,r,l){if(ke(n)){var a=!0;Zl(t)}else a=!1;if(zn(t,l),t.stateNode===null)Ol(e,t),cc(t,n,r),ji(t,n,r,l),r=!0;else if(e===null){var{stateNode:i,memoizedProps:o}=t;i.props=o;var u=i.context,f=n.contextType;typeof f==="object"&&f!==null?f=Ae(f):(f=ke(n)?Jt:ue.current,f=Tn(t,f));var h=n.getDerivedStateFromProps,g=typeof h==="function"||typeof i.getSnapshotBeforeUpdate==="function";g||typeof i.UNSAFE_componentWillReceiveProps!=="function"&&typeof i.componentWillReceiveProps!=="function"||(o!==r||u!==f)&&Ss(t,i,r,f),pt=!1;var v=t.memoizedState;i.state=v,ea(t,r,i,l),u=t.memoizedState,o!==r||v!==u||ye.current||pt?(typeof h==="function"&&(qi(t,n,h,r),u=t.memoizedState),(o=pt||Ns(t,n,o,r,v,u,f))?(g||typeof i.UNSAFE_componentWillMount!=="function"&&typeof i.componentWillMount!=="function"||(typeof i.componentWillMount==="function"&&i.componentWillMount(),typeof i.UNSAFE_componentWillMount==="function"&&i.UNSAFE_componentWillMount()),typeof i.componentDidMount==="function"&&(t.flags|=4194308)):(typeof i.componentDidMount==="function"&&(t.flags|=4194308),t.memoizedProps=r,t.memoizedState=u),i.props=r,i.state=u,i.context=f,r=o):(typeof i.componentDidMount==="function"&&(t.flags|=4194308),r=!1)}else{i=t.stateNode,Wd(e,t),o=t.memoizedProps,f=t.type===t.elementType?o:Le(t.type,o),i.props=f,g=t.pendingProps,v=i.context,u=n.contextType,typeof u==="object"&&u!==null?u=Ae(u):(u=ke(n)?Jt:ue.current,u=Tn(t,u));var S=n.getDerivedStateFromProps;(h=typeof S==="function"||typeof i.getSnapshotBeforeUpdate==="function")||typeof i.UNSAFE_componentWillReceiveProps!=="function"&&typeof i.componentWillReceiveProps!=="function"||(o!==g||v!==u)&&Ss(t,i,r,u),pt=!1,v=t.memoizedState,i.state=v,ea(t,r,i,l);var N=t.memoizedState;o!==g||v!==N||ye.current||pt?(typeof S==="function"&&(qi(t,n,S,r),N=t.memoizedState),(f=pt||Ns(t,n,f,r,v,N,u)||!1)?(h||typeof i.UNSAFE_componentWillUpdate!=="function"&&typeof i.componentWillUpdate!=="function"||(typeof i.componentWillUpdate==="function"&&i.componentWillUpdate(r,N,u),typeof i.UNSAFE_componentWillUpdate==="function"&&i.UNSAFE_componentWillUpdate(r,N,u)),typeof i.componentDidUpdate==="function"&&(t.flags|=4),typeof i.getSnapshotBeforeUpdate==="function"&&(t.flags|=1024)):(typeof i.componentDidUpdate!=="function"||o===e.memoizedProps&&v===e.memoizedState||(t.flags|=4),typeof i.getSnapshotBeforeUpdate!=="function"||o===e.memoizedProps&&v===e.memoizedState||(t.flags|=1024),t.memoizedProps=r,t.memoizedState=N),i.props=r,i.state=N,i.context=u,r=f):(typeof i.componentDidUpdate!=="function"||o===e.memoizedProps&&v===e.memoizedState||(t.flags|=4),typeof i.getSnapshotBeforeUpdate!=="function"||o===e.memoizedProps&&v===e.memoizedState||(t.flags|=1024),r=!1)}return no(e,t,n,r,a,l)}function no(e,t,n,r,l,a){vc(e,t);var i=(t.flags&128)!==0;if(!r&&!i)return l&&ps(t,n,!1),it(e,t,a);r=t.stateNode,T0.current=t;var o=i&&typeof n.getDerivedStateFromError!=="function"?null:r.render();return t.flags|=1,e!==null&&i?(t.child=Fn(t,e.child,null,a),t.child=Fn(t,null,o,a)):de(e,t,o,a),t.memoizedState=r.state,l&&ps(t,n,!0),t.child}function gc(e){var t=e.stateNode;t.pendingContext?fs(e,t.pendingContext,t.pendingContext!==t.context):t.context&&fs(e,t.context,!1),bo(e,t.containerInfo)}function Ms(e,t,n,r,l){return Mn(),Ao(l),t.flags|=256,de(e,t,n,r),t.child}function lo(e){return{baseLanes:e,cachePool:null,transitions:null}}function yc(e,t,n){var r=t.pendingProps,l=H.current,a=!1,i=(t.flags&128)!==0,o;if((o=i)||(o=e!==null&&e.memoizedState===null?!1:(l&2)!==0),o)a=!0,t.flags&=-129;else if(e===null||e.memoizedState!==null)l|=1;if(D(H,l&1),e===null){if(Gi(t),e=t.memoizedState,e!==null&&(e=e.dehydrated,e!==null))return(t.mode&1)===0?t.lanes=1:e.data==="$!"?t.lanes=8:t.lanes=1073741824,null;return i=r.children,e=r.fallback,a?(r=t.mode,a=t.child,i={mode:"hidden",children:i},(r&1)===0&&a!==null?(a.childLanes=0,a.pendingProps=i):a=ka(i,r,0,null),e=Yt(e,r,n,null),a.return=t,e.return=t,a.sibling=e,t.child=a,t.child.memoizedState=lo(n),t.memoizedState=ro,e):Yo(t,i)}if(l=e.memoizedState,l!==null&&(o=l.dehydrated,o!==null))return M0(e,t,i,r,o,l,n);if(a){a=r.fallback,i=t.mode,l=e.child,o=l.sibling;var u={mode:"hidden",children:r.children};return(i&1)===0&&t.child!==l?(r=t.child,r.childLanes=0,r.pendingProps=u,t.deletions=null):(r=zt(l,u),r.subtreeFlags=l.subtreeFlags&14680064),o!==null?a=zt(o,a):(a=Yt(a,i,n,null),a.flags|=2),a.return=t,r.return=t,r.sibling=a,t.child=r,r=a,a=t.child,i=e.child.memoizedState,i=i===null?lo(n):{baseLanes:i.baseLanes|n,cachePool:null,transitions:i.transitions},a.memoizedState=i,a.childLanes=e.childLanes&~n,t.memoizedState=ro,r}return a=e.child,e=a.sibling,r=zt(a,{mode:"visible",children:r.children}),(t.mode&1)===0&&(r.lanes=n),r.return=t,r.sibling=null,e!==null&&(n=t.deletions,n===null?(t.deletions=[e],t.flags|=16):n.push(e)),t.child=r,t.memoizedState=null,r}function Yo(e,t){return t=ka({mode:"visible",children:t},e.mode,0,null),t.return=e,e.child=t}function zl(e,t,n,r){return r!==null&&Ao(r),Fn(t,e.child,null,n),e=Yo(t,t.pendingProps.children),e.flags|=2,t.memoizedState=null,e}function M0(e,t,n,r,l,a,i){if(n){if(t.flags&256)return t.flags&=-257,r=vi(Error(w(422))),zl(e,t,i,r);if(t.memoizedState!==null)return t.child=e.child,t.flags|=128,null;return a=r.fallback,l=t.mode,r=ka({mode:"visible",children:r.children},l,0,null),a=Yt(a,l,i,null),a.flags|=2,r.return=t,a.return=t,r.sibling=a,t.child=r,(t.mode&1)!==0&&Fn(t,e.child,null,i),t.child.memoizedState=lo(i),t.memoizedState=ro,a}if((t.mode&1)===0)return zl(e,t,i,null);if(l.data==="$!"){if(r=l.nextSibling&&l.nextSibling.dataset,r)var o=r.dgst;return r=o,a=Error(w(419)),r=vi(a,r,void 0),zl(e,t,i,r)}if(o=(i&e.childLanes)!==0,ge||o){if(r=ee,r!==null){switch(i&-i){case 4:l=2;break;case 16:l=8;break;case 64:case 128:case 256:case 512:case 1024:case 2048:case 4096:case 8192:case 16384:case 32768:case 65536:case 131072:case 262144:case 524288:case 1048576:case 2097152:case 4194304:case 8388608:case 16777216:case 33554432:case 67108864:l=32;break;case 536870912:l=268435456;break;default:l=0}l=(l&(r.suspendedLanes|i))!==0?0:l,l!==0&&l!==a.retryLane&&(a.retryLane=l,at(e,l),$e(r,e,l,-1))}return jo(),r=vi(Error(w(421))),zl(e,t,i,r)}if(l.data==="$?")return t.flags|=128,t.child=e.child,t=$0.bind(null,e),l._reactRetry=t,null;return e=a.treeContext,Ee=Nt(l.nextSibling),ze=t,b=!0,Ke=null,e!==null&&(Me[Fe++]=et,Me[Fe++]=tt,Me[Fe++]=Zt,et=e.id,tt=e.overflow,Zt=t),t=Yo(t,r.children),t.flags|=4096,t}function Fs(e,t,n){e.lanes|=t;var r=e.alternate;r!==null&&(r.lanes|=t),Xi(e.return,t,n)}function gi(e,t,n,r,l){var a=e.memoizedState;a===null?e.memoizedState={isBackwards:t,rendering:null,renderingStartTime:0,last:r,tail:n,tailMode:l}:(a.isBackwards=t,a.rendering=null,a.renderingStartTime=0,a.last=r,a.tail=n,a.tailMode=l)}function kc(e,t,n){var r=t.pendingProps,l=r.revealOrder,a=r.tail;if(de(e,t,r.children,n),r=H.current,(r&2)!==0)r=r&1|2,t.flags|=128;else{if(e!==null&&(e.flags&128)!==0)e:for(e=t.child;e!==null;){if(e.tag===13)e.memoizedState!==null&&Fs(e,n,t);else if(e.tag===19)Fs(e,n,t);else if(e.child!==null){e.child.return=e,e=e.child;continue}if(e===t)break e;for(;e.sibling===null;){if(e.return===null||e.return===t)break e;e=e.return}e.sibling.return=e.return,e=e.sibling}r&=1}if(D(H,r),(t.mode&1)===0)t.memoizedState=null;else switch(l){case"forwards":n=t.child;for(l=null;n!==null;)e=n.alternate,e!==null&&ta(e)===null&&(l=n),n=n.sibling;n=l,n===null?(l=t.child,t.child=null):(l=n.sibling,n.sibling=null),gi(t,!1,l,n,a);break;case"backwards":n=null,l=t.child;for(t.child=null;l!==null;){if(e=l.alternate,e!==null&&ta(e)===null){t.child=l;break}e=l.sibling,l.sibling=n,n=l,l=e}gi(t,!0,n,null,a);break;case"together":gi(t,!1,null,null,void 0);break;default:t.memoizedState=null}return t.child}function Ol(e,t){(t.mode&1)===0&&e!==null&&(e.alternate=null,t.alternate=null,t.flags|=2)}function it(e,t,n){if(e!==null&&(t.dependencies=e.dependencies),Xt|=t.lanes,(n&t.childLanes)===0)return null;if(e!==null&&t.child!==e.child)throw Error(w(153));if(t.child!==null){e=t.child,n=zt(e,e.pendingProps),t.child=n;for(n.return=t;e.sibling!==null;)e=e.sibling,n=n.sibling=zt(e,e.pendingProps),n.return=t;n.sibling=null}return t.child}function F0(e,t,n){switch(t.tag){case 3:gc(t),Mn();break;case 5:Vd(t);break;case 1:ke(t.type)&&Zl(t);break;case 4:bo(t,t.stateNode.containerInfo);break;case 10:var r=t.type._context,l=t.memoizedProps.value;D(ql,r._currentValue),r._currentValue=l;break;case 13:if(r=t.memoizedState,r!==null){if(r.dehydrated!==null)return D(H,H.current&1),t.flags|=128,null;if((n&t.child.childLanes)!==0)return yc(e,t,n);return D(H,H.current&1),e=it(e,t,n),e!==null?e.sibling:null}D(H,H.current&1);break;case 19:if(r=(n&t.childLanes)!==0,(e.flags&128)!==0){if(r)return kc(e,t,n);t.flags|=128}if(l=t.memoizedState,l!==null&&(l.rendering=null,l.tail=null,l.lastEffect=null),D(H,H.current),r)break;else return null;case 22:case 23:return t.lanes=0,hc(e,t,n)}return it(e,t,n)}function rr(e,t){if(!b)switch(e.tailMode){case"hidden":t=e.tail;for(var n=null;t!==null;)t.alternate!==null&&(n=t),t=t.sibling;n===null?e.tail=null:n.sibling=null;break;case"collapsed":n=e.tail;for(var r=null;n!==null;)n.alternate!==null&&(r=n),n=n.sibling;r===null?t||e.tail===null?e.tail=null:e.tail.sibling=null:r.sibling=null}}function ie(e){var t=e.alternate!==null&&e.alternate.child===e.child,n=0,r=0;if(t)for(var l=e.child;l!==null;)n|=l.lanes|l.childLanes,r|=l.subtreeFlags&14680064,r|=l.flags&14680064,l.return=e,l=l.sibling;else for(l=e.child;l!==null;)n|=l.lanes|l.childLanes,r|=l.subtreeFlags,r|=l.flags,l.return=e,l=l.sibling;return e.subtreeFlags|=r,e.childLanes=n,t}function P0(e,t,n){var r=t.pendingProps;switch(Io(t),t.tag){case 2:case 16:case 15:case 0:case 11:case 7:case 8:case 12:case 9:case 14:return ie(t),null;case 1:return ke(t.type)&&Jl(),ie(t),null;case 3:if(r=t.stateNode,Pn(),L(ye),L(ue),Bo(),r.pendingContext&&(r.context=r.pendingContext,r.pendingContext=null),e===null||e.child===null)xl(t)?t.flags|=4:e===null||e.memoizedState.isDehydrated&&(t.flags&256)===0||(t.flags|=1024,Ke!==null&&(mo(Ke),Ke=null));return ao(e,t),ie(t),null;case 5:Ko(t);var l=Vt(Rr.current);if(n=t.type,e!==null&&t.stateNode!=null)Nc(e,t,n,r,l),e.ref!==t.ref&&(t.flags|=512,t.flags|=2097152);else{if(!r){if(t.stateNode===null)throw Error(w(166));return ie(t),null}if(e=Vt(Ge.current),xl(t)){r=t.stateNode,n=t.type;var a=t.memoizedProps;switch(r[Je]=t,r[Ir]=a,e=(t.mode&1)!==0,n){case"dialog":U("cancel",r),U("close",r);break;case"iframe":case"object":case"embed":U("load",r);break;case"video":case"audio":for(l=0;l<fr.length;l++)U(fr[l],r);break;case"source":U("error",r);break;case"img":case"image":case"link":U("error",r),U("load",r);break;case"details":U("toggle",r);break;case"input":Ku(r,a),U("invalid",r);break;case"select":r._wrapperState={wasMultiple:!!a.multiple},U("invalid",r);break;case"textarea":$u(r,a),U("invalid",r)}Fi(n,a),l=null;for(var i in a)if(a.hasOwnProperty(i)){var o=a[i];i==="children"?typeof o==="string"?r.textContent!==o&&(a.suppressHydrationWarning!==!0&&Sl(r.textContent,o,e),l=["children",o]):typeof o==="number"&&r.textContent!==""+o&&(a.suppressHydrationWarning!==!0&&Sl(r.textContent,o,e),l=["children",""+o]):Sr.hasOwnProperty(i)&&o!=null&&i==="onScroll"&&U("scroll",r)}switch(n){case"input":ml(r),Bu(r,a,!0);break;case"textarea":ml(r),Hu(r);break;case"select":case"option":break;default:typeof a.onClick==="function"&&(r.onclick=Yl)}r=l,t.updateQueue=r,r!==null&&(t.flags|=4)}else{i=l.nodeType===9?l:l.ownerDocument,e==="http://www.w3.org/1999/xhtml"&&(e=Gs(n)),e==="http://www.w3.org/1999/xhtml"?n==="script"?(e=i.createElement("div"),e.innerHTML="<script><\/script>",e=e.removeChild(e.firstChild)):typeof r.is==="string"?e=i.createElement(n,{is:r.is}):(e=i.createElement(n),n==="select"&&(i=e,r.multiple?i.multiple=!0:r.size&&(i.size=r.size))):e=i.createElementNS(e,n),e[Je]=t,e[Ir]=r,wc(e,t,!1,!1),t.stateNode=e;e:{switch(i=Pi(n,r),n){case"dialog":U("cancel",e),U("close",e),l=r;break;case"iframe":case"object":case"embed":U("load",e),l=r;break;case"video":case"audio":for(l=0;l<fr.length;l++)U(fr[l],e);l=r;break;case"source":U("error",e),l=r;break;case"img":case"image":case"link":U("error",e),U("load",e),l=r;break;case"details":U("toggle",e),l=r;break;case"input":Ku(e,r),l=zi(e,r),U("invalid",e);break;case"option":l=r;break;case"select":e._wrapperState={wasMultiple:!!r.multiple},l=V({},r,{value:void 0}),U("invalid",e);break;case"textarea":$u(e,r),l=Ti(e,r),U("invalid",e);break;default:l=r}Fi(n,l),o=l;for(a in o)if(o.hasOwnProperty(a)){var u=o[a];a==="style"?js(e,u):a==="dangerouslySetInnerHTML"?(u=u?u.__html:void 0,u!=null&&Xs(e,u)):a==="children"?typeof u==="string"?(n!=="textarea"||u!=="")&&xr(e,u):typeof u==="number"&&xr(e,""+u):a!=="suppressContentEditableWarning"&&a!=="suppressHydrationWarning"&&a!=="autoFocus"&&(Sr.hasOwnProperty(a)?u!=null&&a==="onScroll"&&U("scroll",e):u!=null&&go(e,a,u,i))}switch(n){case"input":ml(e),Bu(e,r,!1);break;case"textarea":ml(e),Hu(e);break;case"option":r.value!=null&&e.setAttribute("value",""+Ct(r.value));break;case"select":e.multiple=!!r.multiple,a=r.value,a!=null?Nn(e,!!r.multiple,a,!1):r.defaultValue!=null&&Nn(e,!!r.multiple,r.defaultValue,!0);break;default:typeof l.onClick==="function"&&(e.onclick=Yl)}switch(n){case"button":case"input":case"select":case"textarea":r=!!r.autoFocus;break e;case"img":r=!0;break e;default:r=!1}}r&&(t.flags|=4)}t.ref!==null&&(t.flags|=512,t.flags|=2097152)}return ie(t),null;case 6:if(e&&t.stateNode!=null)Sc(e,t,e.memoizedProps,r);else{if(typeof r!=="string"&&t.stateNode===null)throw Error(w(166));if(n=Vt(Rr.current),Vt(Ge.current),xl(t)){if(r=t.stateNode,n=t.memoizedProps,r[Je]=t,a=r.nodeValue!==n){if(e=ze,e!==null)switch(e.tag){case 3:Sl(r.nodeValue,n,(e.mode&1)!==0);break;case 5:e.memoizedProps.suppressHydrationWarning!==!0&&Sl(r.nodeValue,n,(e.mode&1)!==0)}}a&&(t.flags|=4)}else r=(n.nodeType===9?n:n.ownerDocument).createTextNode(r),r[Je]=t,t.stateNode=r}return ie(t),null;case 13:if(L(H),r=t.memoizedState,e===null||e.memoizedState!==null&&e.memoizedState.dehydrated!==null){if(b&&Ee!==null&&(t.mode&1)!==0&&(t.flags&128)===0)Kd(),Mn(),t.flags|=98560,a=!1;else if(a=xl(t),r!==null&&r.dehydrated!==null){if(e===null){if(!a)throw Error(w(318));if(a=t.memoizedState,a=a!==null?a.dehydrated:null,!a)throw Error(w(317));a[Je]=t}else Mn(),(t.flags&128)===0&&(t.memoizedState=null),t.flags|=4;ie(t),a=!1}else Ke!==null&&(mo(Ke),Ke=null),a=!0;if(!a)return t.flags&65536?t:null}if((t.flags&128)!==0)return t.lanes=n,t;return r=r!==null,r!==(e!==null&&e.memoizedState!==null)&&r&&(t.child.flags|=8192,(t.mode&1)!==0&&(e===null||(H.current&1)!==0?X===0&&(X=3):jo())),t.updateQueue!==null&&(t.flags|=4),ie(t),null;case 4:return Pn(),ao(e,t),e===null&&Fr(t.stateNode.containerInfo),ie(t),null;case 10:return Do(t.type._context),ie(t),null;case 17:return ke(t.type)&&Jl(),ie(t),null;case 19:if(L(H),a=t.memoizedState,a===null)return ie(t),null;if(r=(t.flags&128)!==0,i=a.rendering,i===null)if(r)rr(a,!1);else{if(X!==0||e!==null&&(e.flags&128)!==0)for(e=t.child;e!==null;){if(i=ta(e),i!==null){t.flags|=128,rr(a,!1),r=i.updateQueue,r!==null&&(t.updateQueue=r,t.flags|=4),t.subtreeFlags=0,r=n;for(n=t.child;n!==null;)a=n,e=r,a.flags&=14680066,i=a.alternate,i===null?(a.childLanes=0,a.lanes=e,a.child=null,a.subtreeFlags=0,a.memoizedProps=null,a.memoizedState=null,a.updateQueue=null,a.dependencies=null,a.stateNode=null):(a.childLanes=i.childLanes,a.lanes=i.lanes,a.child=i.child,a.subtreeFlags=0,a.deletions=null,a.memoizedProps=i.memoizedProps,a.memoizedState=i.memoizedState,a.updateQueue=i.updateQueue,a.type=i.type,e=i.dependencies,a.dependencies=e===null?null:{lanes:e.lanes,firstContext:e.firstContext}),n=n.sibling;return D(H,H.current&1|2),t.child}e=e.sibling}a.tail!==null&&Y()>An&&(t.flags|=128,r=!0,rr(a,!1),t.lanes=4194304)}else{if(!r)if(e=ta(i),e!==null){if(t.flags|=128,r=!0,n=e.updateQueue,n!==null&&(t.updateQueue=n,t.flags|=4),rr(a,!0),a.tail===null&&a.tailMode==="hidden"&&!i.alternate&&!b)return ie(t),null}else 2*Y()-a.renderingStartTime>An&&n!==1073741824&&(t.flags|=128,r=!0,rr(a,!1),t.lanes=4194304);a.isBackwards?(i.sibling=t.child,t.child=i):(n=a.last,n!==null?n.sibling=i:t.child=i,a.last=i)}if(a.tail!==null)return t=a.tail,a.rendering=t,a.tail=t.sibling,a.renderingStartTime=Y(),t.sibling=null,n=H.current,D(H,r?n&1|2:n&1),t;return ie(t),null;case 22:case 23:return qo(),r=t.memoizedState!==null,e!==null&&e.memoizedState!==null!==r&&(t.flags|=8192),r&&(t.mode&1)!==0?(xe&1073741824)!==0&&(ie(t),t.subtreeFlags&6&&(t.flags|=8192)):ie(t),null;case 24:return null;case 25:return null}throw Error(w(156,t.tag))}function I0(e,t){switch(Io(t),t.tag){case 1:return ke(t.type)&&Jl(),e=t.flags,e&65536?(t.flags=e&-65537|128,t):null;case 3:return Pn(),L(ye),L(ue),Bo(),e=t.flags,(e&65536)!==0&&(e&128)===0?(t.flags=e&-65537|128,t):null;case 5:return Ko(t),null;case 13:if(L(H),e=t.memoizedState,e!==null&&e.dehydrated!==null){if(t.alternate===null)throw Error(w(340));Mn()}return e=t.flags,e&65536?(t.flags=e&-65537|128,t):null;case 19:return L(H),null;case 4:return Pn(),null;case 10:return Do(t.type._context),null;case 22:case 23:return qo(),null;case 24:return null;default:return null}}function kn(e,t){var n=e.ref;if(n!==null)if(typeof n==="function")try{n(null)}catch(r){Q(e,t,r)}else n.current=null}function io(e,t,n){try{n()}catch(r){Q(e,t,r)}}function R0(e,t){if(Hi=Wl,e=_d(),Fo(e)){if("selectionStart"in e)var n={start:e.selectionStart,end:e.selectionEnd};else e:{n=(n=e.ownerDocument)&&n.defaultView||window;var r=n.getSelection&&n.getSelection();if(r&&r.rangeCount!==0){n=r.anchorNode;var{anchorOffset:l,focusNode:a}=r;r=r.focusOffset;try{n.nodeType,a.nodeType}catch(k){n=null;break e}var i=0,o=-1,u=-1,f=0,h=0,g=e,v=null;t:for(;;){for(var S;;){if(g!==n||l!==0&&g.nodeType!==3||(o=i+l),g!==a||r!==0&&g.nodeType!==3||(u=i+r),g.nodeType===3&&(i+=g.nodeValue.length),(S=g.firstChild)===null)break;v=g,g=S}for(;;){if(g===e)break t;if(v===n&&++f===l&&(o=i),v===a&&++h===r&&(u=i),(S=g.nextSibling)!==null)break;g=v,v=g.parentNode}g=S}n=o===-1||u===-1?null:{start:o,end:u}}else n=null}n=n||{start:0,end:0}}else n=null;Wi={focusedElem:e,selectionRange:n},Wl=!1;for(E=t;E!==null;)if(t=E,e=t.child,(t.subtreeFlags&1028)!==0&&e!==null)e.return=t,E=e;else for(;E!==null;){t=E;try{var N=t.alternate;if((t.flags&1024)!==0)switch(t.tag){case 0:case 11:case 15:break;case 1:if(N!==null){var{memoizedProps:x,memoizedState:R}=N,p=t.stateNode,c=p.getSnapshotBeforeUpdate(t.elementType===t.type?x:Le(t.type,x),R);p.__reactInternalSnapshotBeforeUpdate=c}break;case 3:var m=t.stateNode.containerInfo;m.nodeType===1?m.textContent="":m.nodeType===9&&m.documentElement&&m.removeChild(m.documentElement);break;case 5:case 6:case 4:case 17:break;default:throw Error(w(163))}}catch(k){Q(t,t.return,k)}if(e=t.sibling,e!==null){e.return=t.return,E=e;break}E=t.return}return N=Ps,Ps=!1,N}function kr(e,t,n){var r=t.updateQueue;if(r=r!==null?r.lastEffect:null,r!==null){var l=r=r.next;do{if((l.tag&e)===e){var a=l.destroy;l.destroy=void 0,a!==void 0&&io(t,n,a)}l=l.next}while(l!==r)}}function ga(e,t){if(t=t.updateQueue,t=t!==null?t.lastEffect:null,t!==null){var n=t=t.next;do{if((n.tag&e)===e){var r=n.create;n.destroy=r()}n=n.next}while(n!==t)}}function oo(e){var t=e.ref;if(t!==null){var n=e.stateNode;switch(e.tag){case 5:e=n;break;default:e=n}typeof t==="function"?t(e):t.current=e}}function xc(e){var t=e.alternate;t!==null&&(e.alternate=null,xc(t)),e.child=null,e.deletions=null,e.sibling=null,e.tag===5&&(t=e.stateNode,t!==null&&(delete t[Je],delete t[Ir],delete t[Yi],delete t[v0],delete t[g0])),e.stateNode=null,e.return=null,e.dependencies=null,e.memoizedProps=null,e.memoizedState=null,e.pendingProps=null,e.stateNode=null,e.updateQueue=null}function Ec(e){return e.tag===5||e.tag===3||e.tag===4}function Is(e){e:for(;;){for(;e.sibling===null;){if(e.return===null||Ec(e.return))return null;e=e.return}e.sibling.return=e.return;for(e=e.sibling;e.tag!==5&&e.tag!==6&&e.tag!==18;){if(e.flags&2)continue e;if(e.child===null||e.tag===4)continue e;else e.child.return=e,e=e.child}if(!(e.flags&2))return e.stateNode}}function uo(e,t,n){var r=e.tag;if(r===5||r===6)e=e.stateNode,t?n.nodeType===8?n.parentNode.insertBefore(e,t):n.insertBefore(e,t):(n.nodeType===8?(t=n.parentNode,t.insertBefore(e,n)):(t=n,t.appendChild(e)),n=n._reactRootContainer,n!==null&&n!==void 0||t.onclick!==null||(t.onclick=Yl));else if(r!==4&&(e=e.child,e!==null))for(uo(e,t,n),e=e.sibling;e!==null;)uo(e,t,n),e=e.sibling}function so(e,t,n){var r=e.tag;if(r===5||r===6)e=e.stateNode,t?n.insertBefore(e,t):n.appendChild(e);else if(r!==4&&(e=e.child,e!==null))for(so(e,t,n),e=e.sibling;e!==null;)so(e,t,n),e=e.sibling}function ct(e,t,n){for(n=n.child;n!==null;)zc(e,t,n),n=n.sibling}function zc(e,t,n){if(Ze&&typeof Ze.onCommitFiberUnmount==="function")try{Ze.onCommitFiberUnmount(sa,n)}catch(o){}switch(n.tag){case 5:oe||kn(n,t);case 6:var r=te,l=be;te=null,ct(e,t,n),te=r,be=l,te!==null&&(be?(e=te,n=n.stateNode,e.nodeType===8?e.parentNode.removeChild(n):e.removeChild(n)):te.removeChild(n.stateNode));break;case 18:te!==null&&(be?(e=te,n=n.stateNode,e.nodeType===8?di(e.parentNode,n):e.nodeType===1&&di(e,n),_r(e)):di(te,n.stateNode));break;case 4:r=te,l=be,te=n.stateNode.containerInfo,be=!0,ct(e,t,n),te=r,be=l;break;case 0:case 11:case 14:case 15:if(!oe&&(r=n.updateQueue,r!==null&&(r=r.lastEffect,r!==null))){l=r=r.next;do{var a=l,i=a.destroy;a=a.tag,i!==void 0&&((a&2)!==0?io(n,t,i):(a&4)!==0&&io(n,t,i)),l=l.next}while(l!==r)}ct(e,t,n);break;case 1:if(!oe&&(kn(n,t),r=n.stateNode,typeof r.componentWillUnmount==="function"))try{r.props=n.memoizedProps,r.state=n.memoizedState,r.componentWillUnmount()}catch(o){Q(n,t,o)}ct(e,t,n);break;case 21:ct(e,t,n);break;case 22:n.mode&1?(oe=(r=oe)||n.memoizedState!==null,ct(e,t,n),oe=r):ct(e,t,n);break;default:ct(e,t,n)}}function As(e){var t=e.updateQueue;if(t!==null){e.updateQueue=null;var n=e.stateNode;n===null&&(n=e.stateNode=new A0),t.forEach(function(r){var l=H0.bind(null,e,r);n.has(r)||(n.add(r),r.then(l,l))})}}function Ue(e,t){var n=t.deletions;if(n!==null)for(var r=0;r<n.length;r++){var l=n[r];try{var a=e,i=t,o=i;e:for(;o!==null;){switch(o.tag){case 5:te=o.stateNode,be=!1;break e;case 3:te=o.stateNode.containerInfo,be=!0;break e;case 4:te=o.stateNode.containerInfo,be=!0;break e}o=o.return}if(te===null)throw Error(w(160));zc(a,i,l),te=null,be=!1;var u=l.alternate;u!==null&&(u.return=null),l.return=null}catch(f){Q(l,t,f)}}if(t.subtreeFlags&12854)for(t=t.child;t!==null;)Cc(t,e),t=t.sibling}function Cc(e,t){var{alternate:n,flags:r}=e;switch(e.tag){case 0:case 11:case 14:case 15:if(Ue(t,e),Qe(e),r&4){try{kr(3,e,e.return),ga(3,e)}catch(x){Q(e,e.return,x)}try{kr(5,e,e.return)}catch(x){Q(e,e.return,x)}}break;case 1:Ue(t,e),Qe(e),r&512&&n!==null&&kn(n,n.return);break;case 5:if(Ue(t,e),Qe(e),r&512&&n!==null&&kn(n,n.return),e.flags&32){var l=e.stateNode;try{xr(l,"")}catch(x){Q(e,e.return,x)}}if(r&4&&(l=e.stateNode,l!=null)){var a=e.memoizedProps,i=n!==null?n.memoizedProps:a,o=e.type,u=e.updateQueue;if(e.updateQueue=null,u!==null)try{o==="input"&&a.type==="radio"&&a.name!=null&&Js(l,a),Pi(o,i);var f=Pi(o,a);for(i=0;i<u.length;i+=2){var h=u[i],g=u[i+1];h==="style"?js(l,g):h==="dangerouslySetInnerHTML"?Xs(l,g):h==="children"?xr(l,g):go(l,h,g,f)}switch(o){case"input":Ci(l,a);break;case"textarea":Zs(l,a);break;case"select":var v=l._wrapperState.wasMultiple;l._wrapperState.wasMultiple=!!a.multiple;var S=a.value;S!=null?Nn(l,!!a.multiple,S,!1):v!==!!a.multiple&&(a.defaultValue!=null?Nn(l,!!a.multiple,a.defaultValue,!0):Nn(l,!!a.multiple,a.multiple?[]:"",!1))}l[Ir]=a}catch(x){Q(e,e.return,x)}}break;case 6:if(Ue(t,e),Qe(e),r&4){if(e.stateNode===null)throw Error(w(162));l=e.stateNode,a=e.memoizedProps;try{l.nodeValue=a}catch(x){Q(e,e.return,x)}}break;case 3:if(Ue(t,e),Qe(e),r&4&&n!==null&&n.memoizedState.isDehydrated)try{_r(t.containerInfo)}catch(x){Q(e,e.return,x)}break;case 4:Ue(t,e),Qe(e);break;case 13:Ue(t,e),Qe(e),l=e.child,l.flags&8192&&(a=l.memoizedState!==null,l.stateNode.isHidden=a,!a||l.alternate!==null&&l.alternate.memoizedState!==null||(Go=Y())),r&4&&As(e);break;case 22:if(h=n!==null&&n.memoizedState!==null,e.mode&1?(oe=(f=oe)||h,Ue(t,e),oe=f):Ue(t,e),Qe(e),r&8192){if(f=e.memoizedState!==null,(e.stateNode.isHidden=f)&&!h&&(e.mode&1)!==0)for(E=e,h=e.child;h!==null;){for(g=E=h;E!==null;){switch(v=E,S=v.child,v.tag){case 0:case 11:case 14:case 15:kr(4,v,v.return);break;case 1:kn(v,v.return);var N=v.stateNode;if(typeof N.componentWillUnmount==="function"){r=v,n=v.return;try{t=r,N.props=t.memoizedProps,N.state=t.memoizedState,N.componentWillUnmount()}catch(x){Q(r,n,x)}}break;case 5:kn(v,v.return);break;case 22:if(v.memoizedState!==null){Os(g);continue}}S!==null?(S.return=v,E=S):Os(g)}h=h.sibling}e:for(h=null,g=e;;){if(g.tag===5){if(h===null){h=g;try{l=g.stateNode,f?(a=l.style,typeof a.setProperty==="function"?a.setProperty("display","none","important"):a.display="none"):(o=g.stateNode,u=g.memoizedProps.style,i=u!==void 0&&u!==null&&u.hasOwnProperty("display")?u.display:null,o.style.display=qs("display",i))}catch(x){Q(e,e.return,x)}}}else if(g.tag===6){if(h===null)try{g.stateNode.nodeValue=f?"":g.memoizedProps}catch(x){Q(e,e.return,x)}}else if((g.tag!==22&&g.tag!==23||g.memoizedState===null||g===e)&&g.child!==null){g.child.return=g,g=g.child;continue}if(g===e)break e;for(;g.sibling===null;){if(g.return===null||g.return===e)break e;h===g&&(h=null),g=g.return}h===g&&(h=null),g.sibling.return=g.return,g=g.sibling}}break;case 19:Ue(t,e),Qe(e),r&4&&As(e);break;case 21:break;default:Ue(t,e),Qe(e)}}function Qe(e){var t=e.flags;if(t&2){try{e:{for(var n=e.return;n!==null;){if(Ec(n)){var r=n;break e}n=n.return}throw Error(w(160))}switch(r.tag){case 5:var l=r.stateNode;r.flags&32&&(xr(l,""),r.flags&=-33);var a=Is(e);so(e,a,l);break;case 3:case 4:var i=r.stateNode.containerInfo,o=Is(e);uo(e,o,i);break;default:throw Error(w(161))}}catch(u){Q(e,e.return,u)}e.flags&=-3}t&4096&&(e.flags&=-4097)}function O0(e,t,n){E=e,_c(e,t,n)}function _c(e,t,n){for(var r=(e.mode&1)!==0;E!==null;){var l=E,a=l.child;if(l.tag===22&&r){var i=l.memoizedState!==null||Cl;if(!i){var o=l.alternate,u=o!==null&&o.memoizedState!==null||oe;o=Cl;var f=oe;if(Cl=i,(oe=u)&&!f)for(E=l;E!==null;)i=E,u=i.child,i.tag===22&&i.memoizedState!==null?Ds(l):u!==null?(u.return=i,E=u):Ds(l);for(;a!==null;)E=a,_c(a,t,n),a=a.sibling;E=l,Cl=o,oe=f}Rs(e,t,n)}else(l.subtreeFlags&8772)!==0&&a!==null?(a.return=l,E=a):Rs(e,t,n)}}function Rs(e){for(;E!==null;){var t=E;if((t.flags&8772)!==0){var n=t.alternate;try{if((t.flags&8772)!==0)switch(t.tag){case 0:case 11:case 15:oe||ga(5,t);break;case 1:var r=t.stateNode;if(t.flags&4&&!oe)if(n===null)r.componentDidMount();else{var l=t.elementType===t.type?n.memoizedProps:Le(t.type,n.memoizedProps);r.componentDidUpdate(l,n.memoizedState,r.__reactInternalSnapshotBeforeUpdate)}var a=t.updateQueue;a!==null&&ys(t,a,r);break;case 3:var i=t.updateQueue;if(i!==null){if(n=null,t.child!==null)switch(t.child.tag){case 5:n=t.child.stateNode;break;case 1:n=t.child.stateNode}ys(t,i,n)}break;case 5:var o=t.stateNode;if(n===null&&t.flags&4){n=o;var u=t.memoizedProps;switch(t.type){case"button":case"input":case"select":case"textarea":u.autoFocus&&n.focus();break;case"img":u.src&&(n.src=u.src)}}break;case 6:break;case 4:break;case 12:break;case 13:if(t.memoizedState===null){var f=t.alternate;if(f!==null){var h=f.memoizedState;if(h!==null){var g=h.dehydrated;g!==null&&_r(g)}}}break;case 19:case 17:case 21:case 22:case 23:case 25:break;default:throw Error(w(163))}oe||t.flags&512&&oo(t)}catch(v){Q(t,t.return,v)}}if(t===e){E=null;break}if(n=t.sibling,n!==null){n.return=t.return,E=n;break}E=t.return}}function Os(e){for(;E!==null;){var t=E;if(t===e){E=null;break}var n=t.sibling;if(n!==null){n.return=t.return,E=n;break}E=t.return}}function Ds(e){for(;E!==null;){var t=E;try{switch(t.tag){case 0:case 11:case 15:var n=t.return;try{ga(4,t)}catch(u){Q(t,n,u)}break;case 1:var r=t.stateNode;if(typeof r.componentDidMount==="function"){var l=t.return;try{r.componentDidMount()}catch(u){Q(t,l,u)}}var a=t.return;try{oo(t)}catch(u){Q(t,a,u)}break;case 5:var i=t.return;try{oo(t)}catch(u){Q(t,i,u)}}}catch(u){Q(t,t.return,u)}if(t===e){E=null;break}var o=t.sibling;if(o!==null){o.return=t.return,E=o;break}E=t.return}}function ce(){return(P&6)!==0?Y():Dl!==-1?Dl:Dl=Y()}function Et(e){if((e.mode&1)===0)return 1;if((P&2)!==0&&ne!==0)return ne&-ne;if(k0.transition!==null)return Ul===0&&(Ul=cd()),Ul;if(e=O,e!==0)return e;return e=window.event,e=e===void 0?16:yd(e.type),e}function $e(e,t,n,r){if(50<Nr)throw Nr=0,fo=null,Error(w(185));if(br(e,n,r),(P&2)===0||e!==ee)e===ee&&((P&2)===0&&(ya|=n),X===4&&ht(e,ne)),we(e,r),n===1&&P===0&&(t.mode&1)===0&&(An=Y()+500,ma&&Ft())}function we(e,t){var n=e.callbackNode;Nm(e,t);var r=Hl(e,e===ee?ne:0);if(r===0)n!==null&&Qu(n),e.callbackNode=null,e.callbackPriority=0;else if(t=r&-r,e.callbackPriority!==t){if(n!=null&&Qu(n),t===1)e.tag===0?y0(Us.bind(null,e)):Ud(Us.bind(null,e)),m0(function(){(P&6)===0&&Ft()}),n=null;else{switch(fd(r)){case 1:n=So;break;case 4:n=sd;break;case 16:n=$l;break;case 536870912:n=dd;break;default:n=$l}n=Oc(n,Tc.bind(null,e))}e.callbackPriority=t,e.callbackNode=n}}function Tc(e,t){if(Dl=-1,Ul=0,(P&6)!==0)throw Error(w(327));var n=e.callbackNode;if(Cn()&&e.callbackNode!==n)return null;var r=Hl(e,e===ee?ne:0);if(r===0)return null;if((r&30)!==0||(r&e.expiredLanes)!==0||t)t=oa(e,r);else{t=r;var l=P;P|=2;var a=Fc();if(ee!==e||ne!==t)qe=null,An=Y()+500,Qt(e,t);do try{b0();break}catch(o){Mc(e,o)}while(1);Oo(),la.current=a,P=l,J!==null?t=0:(ee=null,ne=0,t=X)}if(t!==0){if(t===2&&(l=Di(e),l!==0&&(r=l,t=po(e,l))),t===1)throw n=Lr,Qt(e,0),ht(e,r),we(e,Y()),n;if(t===6)ht(e,r);else{if(l=e.current.alternate,(r&30)===0&&!U0(l)&&(t=oa(e,r),t===2&&(a=Di(e),a!==0&&(r=a,t=po(e,a))),t===1))throw n=Lr,Qt(e,0),ht(e,r),we(e,Y()),n;switch(e.finishedWork=l,e.finishedLanes=r,t){case 0:case 1:throw Error(w(345));case 2:$t(e,ve,qe);break;case 3:if(ht(e,r),(r&130023424)===r&&(t=Go+500-Y(),10<t)){if(Hl(e,0)!==0)break;if(l=e.suspendedLanes,(l&r)!==r){ce(),e.pingedLanes|=e.suspendedLanes&l;break}e.timeoutHandle=Qi($t.bind(null,e,ve,qe),t);break}$t(e,ve,qe);break;case 4:if(ht(e,r),(r&4194240)===r)break;t=e.eventTimes;for(l=-1;0<r;){var i=31-Be(r);a=1<<i,i=t[i],i>l&&(l=i),r&=~a}if(r=l,r=Y()-r,r=(120>r?120:480>r?480:1080>r?1080:1920>r?1920:3000>r?3000:4320>r?4320:1960*D0(r/1960))-r,10<r){e.timeoutHandle=Qi($t.bind(null,e,ve,qe),r);break}$t(e,ve,qe);break;case 5:$t(e,ve,qe);break;default:throw Error(w(329))}}}return we(e,Y()),e.callbackNode===n?Tc.bind(null,e):null}function po(e,t){var n=wr;return e.current.memoizedState.isDehydrated&&(Qt(e,t).flags|=256),e=oa(e,t),e!==2&&(t=ve,ve=n,t!==null&&mo(t)),e}function mo(e){ve===null?ve=e:ve.push.apply(ve,e)}function U0(e){for(var t=e;;){if(t.flags&16384){var n=t.updateQueue;if(n!==null&&(n=n.stores,n!==null))for(var r=0;r<n.length;r++){var l=n[r],a=l.getSnapshot;l=l.value;try{if(!He(a(),l))return!1}catch(i){return!1}}}if(n=t.child,t.subtreeFlags&16384&&n!==null)n.return=t,t=n;else{if(t===e)break;for(;t.sibling===null;){if(t.return===null||t.return===e)return!0;t=t.return}t.sibling.return=t.return,t=t.sibling}}return!0}function ht(e,t){t&=~Zo,t&=~ya,e.suspendedLanes|=t,e.pingedLanes&=~t;for(e=e.expirationTimes;0<t;){var n=31-Be(t),r=1<<n;e[n]=-1,t&=~r}}function Us(e){if((P&6)!==0)throw Error(w(327));Cn();var t=Hl(e,0);if((t&1)===0)return we(e,Y()),null;var n=oa(e,t);if(e.tag!==0&&n===2){var r=Di(e);r!==0&&(t=r,n=po(e,r))}if(n===1)throw n=Lr,Qt(e,0),ht(e,t),we(e,Y()),n;if(n===6)throw Error(w(345));return e.finishedWork=e.current.alternate,e.finishedLanes=t,$t(e,ve,qe),we(e,Y()),null}function Xo(e,t){var n=P;P|=1;try{return e(t)}finally{P=n,P===0&&(An=Y()+500,ma&&Ft())}}function qt(e){gt!==null&&gt.tag===0&&(P&6)===0&&Cn();var t=P;P|=1;var n=Ie.transition,r=O;try{if(Ie.transition=null,O=1,e)return e()}finally{O=r,Ie.transition=n,P=t,(P&6)===0&&Ft()}}function qo(){xe=wn.current,L(wn)}function Qt(e,t){e.finishedWork=null,e.finishedLanes=0;var n=e.timeoutHandle;if(n!==-1&&(e.timeoutHandle=-1,p0(n)),J!==null)for(n=J.return;n!==null;){var r=n;switch(Io(r),r.tag){case 1:r=r.type.childContextTypes,r!==null&&r!==void 0&&Jl();break;case 3:Pn(),L(ye),L(ue),Bo();break;case 5:Ko(r);break;case 4:Pn();break;case 13:L(H);break;case 19:L(H);break;case 10:Do(r.type._context);break;case 22:case 23:qo()}n=n.return}if(ee=e,J=e=zt(e.current,null),ne=xe=t,X=0,Lr=null,Zo=ya=Xt=0,ve=wr=null,Wt!==null){for(t=0;t<Wt.length;t++)if(n=Wt[t],r=n.interleaved,r!==null){n.interleaved=null;var l=r.next,a=n.pending;if(a!==null){var i=a.next;a.next=l,r.next=i}n.pending=r}Wt=null}return e}function Mc(e,t){do{var n=J;try{if(Oo(),Al.current=ra,na){for(var r=W.memoizedState;r!==null;){var l=r.queue;l!==null&&(l.pending=null),r=r.next}na=!1}if(Gt=0,j=G=W=null,yr=!1,Or=0,Jo.current=null,n===null||n.return===null){X=1,Lr=t,J=null;break}e:{var a=e,i=n.return,o=n,u=t;if(t=ne,o.flags|=32768,u!==null&&typeof u==="object"&&typeof u.then==="function"){var f=u,h=o,g=h.tag;if((h.mode&1)===0&&(g===0||g===11||g===15)){var v=h.alternate;v?(h.updateQueue=v.updateQueue,h.memoizedState=v.memoizedState,h.lanes=v.lanes):(h.updateQueue=null,h.memoizedState=null)}var S=Es(i);if(S!==null){S.flags&=-257,zs(S,i,o,a,t),S.mode&1&&xs(a,f,t),t=S,u=f;var N=t.updateQueue;if(N===null){var x=new Set;x.add(u),t.updateQueue=x}else N.add(u);break e}else{if((t&1)===0){xs(a,f,t),jo();break e}u=Error(w(426))}}else if(b&&o.mode&1){var R=Es(i);if(R!==null){(R.flags&65536)===0&&(R.flags|=256),zs(R,i,o,a,t),Ao(In(u,o));break e}}a=u=In(u,o),X!==4&&(X=2),wr===null?wr=[a]:wr.push(a),a=i;do{switch(a.tag){case 3:a.flags|=65536,t&=-t,a.lanes|=t;var p=fc(a,u,t);gs(a,p);break e;case 1:o=u;var{type:c,stateNode:m}=a;if((a.flags&128)===0&&(typeof c.getDerivedStateFromError==="function"||m!==null&&typeof m.componentDidCatch==="function"&&(xt===null||!xt.has(m)))){a.flags|=65536,t&=-t,a.lanes|=t;var k=pc(a,o,t);gs(a,k);break e}}a=a.return}while(a!==null)}Ic(n)}catch(z){t=z,J===n&&n!==null&&(J=n=n.return);continue}break}while(1)}function Fc(){var e=la.current;return la.current=ra,e===null?ra:e}function jo(){if(X===0||X===3||X===2)X=4;ee===null||(Xt&268435455)===0&&(ya&268435455)===0||ht(ee,ne)}function oa(e,t){var n=P;P|=2;var r=Fc();if(ee!==e||ne!==t)qe=null,Qt(e,t);do try{L0();break}catch(l){Mc(e,l)}while(1);if(Oo(),P=n,la.current=r,J!==null)throw Error(w(261));return ee=null,ne=0,X}function L0(){for(;J!==null;)Pc(J)}function b0(){for(;J!==null&&!fm();)Pc(J)}function Pc(e){var t=Rc(e.alternate,e,xe);e.memoizedProps=e.pendingProps,t===null?Ic(e):J=t,Jo.current=null}function Ic(e){var t=e;do{var n=t.alternate;if(e=t.return,(t.flags&32768)===0){if(n=P0(n,t,xe),n!==null){J=n;return}}else{if(n=I0(n,t),n!==null){n.flags&=32767,J=n;return}if(e!==null)e.flags|=32768,e.subtreeFlags=0,e.deletions=null;else{X=6,J=null;return}}if(t=t.sibling,t!==null){J=t;return}J=t=e}while(t!==null);X===0&&(X=5)}function $t(e,t,n){var r=O,l=Ie.transition;try{Ie.transition=null,O=1,K0(e,t,n,r)}finally{Ie.transition=l,O=r}return null}function K0(e,t,n,r){do Cn();while(gt!==null);if((P&6)!==0)throw Error(w(327));n=e.finishedWork;var l=e.finishedLanes;if(n===null)return null;if(e.finishedWork=null,e.finishedLanes=0,n===e.current)throw Error(w(177));e.callbackNode=null,e.callbackPriority=0;var a=n.lanes|n.childLanes;if(Sm(e,a),e===ee&&(J=ee=null,ne=0),(n.subtreeFlags&2064)===0&&(n.flags&2064)===0||_l||(_l=!0,Oc($l,function(){return Cn(),null})),a=(n.flags&15990)!==0,(n.subtreeFlags&15990)!==0||a){a=Ie.transition,Ie.transition=null;var i=O;O=1;var o=P;P|=4,Jo.current=null,R0(e,n),Cc(n,e),u0(Wi),Wl=!!Hi,Wi=Hi=null,e.current=n,O0(n,e,l),pm(),P=o,O=i,Ie.transition=a}else e.current=n;if(_l&&(_l=!1,gt=e,ia=l),a=e.pendingLanes,a===0&&(xt=null),vm(n.stateNode,r),we(e,Y()),t!==null)for(r=e.onRecoverableError,n=0;n<t.length;n++)l=t[n],r(l.value,{componentStack:l.stack,digest:l.digest});if(aa)throw aa=!1,e=co,co=null,e;return(ia&1)!==0&&e.tag!==0&&Cn(),a=e.pendingLanes,(a&1)!==0?e===fo?Nr++:(Nr=0,fo=e):Nr=0,Ft(),null}function Cn(){if(gt!==null){var e=fd(ia),t=Ie.transition,n=O;try{if(Ie.transition=null,O=16>e?16:e,gt===null)var r=!1;else{if(e=gt,gt=null,ia=0,(P&6)!==0)throw Error(w(331));var l=P;P|=4;for(E=e.current;E!==null;){var a=E,i=a.child;if((E.flags&16)!==0){var o=a.deletions;if(o!==null){for(var u=0;u<o.length;u++){var f=o[u];for(E=f;E!==null;){var h=E;switch(h.tag){case 0:case 11:case 15:kr(8,h,a)}var g=h.child;if(g!==null)g.return=h,E=g;else for(;E!==null;){h=E;var{sibling:v,return:S}=h;if(xc(h),h===f){E=null;break}if(v!==null){v.return=S,E=v;break}E=S}}}var N=a.alternate;if(N!==null){var x=N.child;if(x!==null){N.child=null;do{var R=x.sibling;x.sibling=null,x=R}while(x!==null)}}E=a}}if((a.subtreeFlags&2064)!==0&&i!==null)i.return=a,E=i;else e:for(;E!==null;){if(a=E,(a.flags&2048)!==0)switch(a.tag){case 0:case 11:case 15:kr(9,a,a.return)}var p=a.sibling;if(p!==null){p.return=a.return,E=p;break e}E=a.return}}var c=e.current;for(E=c;E!==null;){i=E;var m=i.child;if((i.subtreeFlags&2064)!==0&&m!==null)m.return=i,E=m;else e:for(i=c;E!==null;){if(o=E,(o.flags&2048)!==0)try{switch(o.tag){case 0:case 11:case 15:ga(9,o)}}catch(z){Q(o,o.return,z)}if(o===i){E=null;break e}var k=o.sibling;if(k!==null){k.return=o.return,E=k;break e}E=o.return}}if(P=l,Ft(),Ze&&typeof Ze.onPostCommitFiberRoot==="function")try{Ze.onPostCommitFiberRoot(sa,e)}catch(z){}r=!0}return r}finally{O=n,Ie.transition=t}}return!1}function Ls(e,t,n){t=In(n,t),t=fc(e,t,1),e=St(e,t,1),t=ce(),e!==null&&(br(e,1,t),we(e,t))}function Q(e,t,n){if(e.tag===3)Ls(e,e,n);else for(;t!==null;){if(t.tag===3){Ls(t,e,n);break}else if(t.tag===1){var r=t.stateNode;if(typeof t.type.getDerivedStateFromError==="function"||typeof r.componentDidCatch==="function"&&(xt===null||!xt.has(r))){e=In(n,e),e=pc(t,e,1),t=St(t,e,1),e=ce(),t!==null&&(br(t,1,e),we(t,e));break}}t=t.return}}function B0(e,t,n){var r=e.pingCache;r!==null&&r.delete(t),t=ce(),e.pingedLanes|=e.suspendedLanes&n,ee===e&&(ne&n)===n&&(X===4||X===3&&(ne&130023424)===ne&&500>Y()-Go?Qt(e,0):Zo|=n),we(e,t)}function Ac(e,t){t===0&&((e.mode&1)===0?t=1:(t=gl,gl<<=1,(gl&130023424)===0&&(gl=4194304)));var n=ce();e=at(e,t),e!==null&&(br(e,t,n),we(e,n))}function $0(e){var t=e.memoizedState,n=0;t!==null&&(n=t.retryLane),Ac(e,n)}function H0(e,t){var n=0;switch(e.tag){case 13:var{stateNode:r,memoizedState:l}=e;l!==null&&(n=l.retryLane);break;case 19:r=e.stateNode;break;default:throw Error(w(314))}r!==null&&r.delete(t),Ac(e,n)}function Oc(e,t){return ud(e,t)}function W0(e,t,n,r){this.tag=e,this.key=n,this.sibling=this.child=this.return=this.stateNode=this.type=this.elementType=null,this.index=0,this.ref=null,this.pendingProps=t,this.dependencies=this.memoizedState=this.updateQueue=this.memoizedProps=null,this.mode=r,this.subtreeFlags=this.flags=0,this.deletions=null,this.childLanes=this.lanes=0,this.alternate=null}function Pe(e,t,n,r){return new W0(e,t,n,r)}function eu(e){return e=e.prototype,!(!e||!e.isReactComponent)}function V0(e){if(typeof e==="function")return eu(e)?1:0;if(e!==void 0&&e!==null){if(e=e.$$typeof,e===ko)return 11;if(e===wo)return 14}return 2}function zt(e,t){var n=e.alternate;return n===null?(n=Pe(e.tag,t,e.key,e.mode),n.elementType=e.elementType,n.type=e.type,n.stateNode=e.stateNode,n.alternate=e,e.alternate=n):(n.pendingProps=t,n.type=e.type,n.flags=0,n.subtreeFlags=0,n.deletions=null),n.flags=e.flags&14680064,n.childLanes=e.childLanes,n.lanes=e.lanes,n.child=e.child,n.memoizedProps=e.memoizedProps,n.memoizedState=e.memoizedState,n.updateQueue=e.updateQueue,t=e.dependencies,n.dependencies=t===null?null:{lanes:t.lanes,firstContext:t.firstContext},n.sibling=e.sibling,n.index=e.index,n.ref=e.ref,n}function Ll(e,t,n,r,l,a){var i=2;if(r=e,typeof e==="function")eu(e)&&(i=1);else if(typeof e==="string")i=5;else e:switch(e){case dn:return Yt(n.children,l,a,t);case yo:i=8,l|=8;break;case Ni:return e=Pe(12,n,t,l|2),e.elementType=Ni,e.lanes=a,e;case Si:return e=Pe(13,n,t,l),e.elementType=Si,e.lanes=a,e;case xi:return e=Pe(19,n,t,l),e.elementType=xi,e.lanes=a,e;case Vs:return ka(n,l,a,t);default:if(typeof e==="object"&&e!==null)switch(e.$$typeof){case Hs:i=10;break e;case Ws:i=9;break e;case ko:i=11;break e;case wo:i=14;break e;case ft:i=16,r=null;break e}throw Error(w(130,e==null?e:typeof e,""))}return t=Pe(i,n,t,l),t.elementType=e,t.type=r,t.lanes=a,t}function Yt(e,t,n,r){return e=Pe(7,e,r,t),e.lanes=n,e}function ka(e,t,n,r){return e=Pe(22,e,r,t),e.elementType=Vs,e.lanes=n,e.stateNode={isHidden:!1},e}function yi(e,t,n){return e=Pe(6,e,null,t),e.lanes=n,e}function ki(e,t,n){return t=Pe(4,e.children!==null?e.children:[],e.key,t),t.lanes=n,t.stateNode={containerInfo:e.containerInfo,pendingChildren:null,implementation:e.implementation},t}function Q0(e,t,n,r,l){this.tag=t,this.containerInfo=e,this.finishedWork=this.pingCache=this.current=this.pendingChildren=null,this.timeoutHandle=-1,this.callbackNode=this.pendingContext=this.context=null,this.callbackPriority=0,this.eventTimes=ri(0),this.expirationTimes=ri(-1),this.entangledLanes=this.finishedLanes=this.mutableReadLanes=this.expiredLanes=this.pingedLanes=this.suspendedLanes=this.pendingLanes=0,this.entanglements=ri(0),this.identifierPrefix=r,this.onRecoverableError=l,this.mutableSourceEagerHydrationData=null}function tu(e,t,n,r,l,a,i,o,u){return e=new Q0(e,t,n,o,u),t===1?(t=1,a===!0&&(t|=8)):t=0,a=Pe(3,null,null,t),e.current=a,a.stateNode=e,a.memoizedState={element:r,isDehydrated:n,cache:null,transitions:null,pendingSuspenseBoundaries:null},Lo(a),e}function Y0(e,t,n){var r=3<arguments.length&&arguments[3]!==void 0?arguments[3]:null;return{$$typeof:sn,key:r==null?null:""+r,children:e,containerInfo:t,implementation:n}}function Dc(e){if(!e)return _t;e=e._reactInternals;e:{if(en(e)!==e||e.tag!==1)throw Error(w(170));var t=e;do{switch(t.tag){case 3:t=t.stateNode.context;break e;case 1:if(ke(t.type)){t=t.stateNode.__reactInternalMemoizedMergedChildContext;break e}}t=t.return}while(t!==null);throw Error(w(171))}if(e.tag===1){var n=e.type;if(ke(n))return Dd(e,n,t)}return t}function Uc(e,t,n,r,l,a,i,o,u){return e=tu(n,r,!0,e,l,a,i,o,u),e.context=Dc(null),n=e.current,r=ce(),l=Et(n),a=nt(r,l),a.callback=t!==void 0&&t!==null?t:null,St(n,a,l),e.current.lanes=l,br(e,l,r),we(e,r),e}function wa(e,t,n,r){var l=t.current,a=ce(),i=Et(l);return n=Dc(n),t.context===null?t.context=n:t.pendingContext=n,t=nt(a,i),t.payload={element:e},r=r===void 0?null:r,r!==null&&(t.callback=r),e=St(l,t,i),e!==null&&($e(e,l,i,a),Il(e,l,i)),i}function ua(e){if(e=e.current,!e.child)return null;switch(e.child.tag){case 5:return e.child.stateNode;default:return e.child.stateNode}}function bs(e,t){if(e=e.memoizedState,e!==null&&e.dehydrated!==null){var n=e.retryLane;e.retryLane=n!==0&&n<t?n:t}}function nu(e,t){bs(e,t),(e=e.alternate)&&bs(e,t)}function J0(){return null}function ru(e){this._internalRoot=e}function Na(e){this._internalRoot=e}function lu(e){return!(!e||e.nodeType!==1&&e.nodeType!==9&&e.nodeType!==11)}function Sa(e){return!(!e||e.nodeType!==1&&e.nodeType!==9&&e.nodeType!==11&&(e.nodeType!==8||e.nodeValue!==" react-mount-point-unstable "))}function Ks(){}function Z0(e,t,n,r,l){if(l){if(typeof r==="function"){var a=r;r=function(){var f=ua(i);a.call(f)}}var i=Uc(t,r,e,0,null,!1,!1,"",Ks);return e._reactRootContainer=i,e[lt]=i.current,Fr(e.nodeType===8?e.parentNode:e),qt(),i}for(;l=e.lastChild;)e.removeChild(l);if(typeof r==="function"){var o=r;r=function(){var f=ua(u);o.call(f)}}var u=tu(e,0,!1,null,null,!1,!1,"",Ks);return e._reactRootContainer=u,e[lt]=u.current,Fr(e.nodeType===8?e.parentNode:e),qt(function(){wa(t,u,n,r)}),u}function xa(e,t,n,r,l){var a=n._reactRootContainer;if(a){var i=a;if(typeof l==="function"){var o=l;l=function(){var u=ua(i);o.call(u)}}wa(t,i,e,l)}else i=Z0(n,t,e,l,r);return ua(i)}var Bs,K,$s,Sr,rt,wi,qp,Uu,Lu,re,ho,ot,pl,sn,dn,yo,Ni,Hs,Ws,ko,Si,xi,wo,ft,Vs,bu,V,ja,ei=!1,ir,hl,Xs,pr,am,im,Ii=null,Ai=null,Sn=null,xn=null,ni=!1,Ri=!1,Kt,mr=!1,Kl=null,Bl=!1,Oi=null,um,ud,Qu,fm,pm,Y,mm,So,sd,$l,hm,dd,sa=null,Ze=null,Be,gm,ym,vl=64,gl=4194304,O=0,pd,Eo,md,hd,vd,Ui=!1,yl,yt=null,kt=null,wt=null,zr,Cr,mt,xm,En,Wl=!0,Vl=null,vt=null,Co=null,Ml=null,Rn,_o,Kr,Tm,li,ai,tr,da,Gu,Mm,Fm,Pm,ii,Im,Am,Rm,Om,Dm,Xu,Um,Lm,bm,Bm,$m,Hm,qu,Wm,Vm,Qm,Ym,Jm,Zm,Gm,Mo,hr=null,Xm,wd,ju,es=!1,cn=!1,e0,vr=null,Tr=null,Ed=!1,ur,sr,Pl,He,s0,fn=null,bi=null,gr=null,Ki=!1,pn,oi,Td,Md,Fd,Pd,Id,Ad,is,cr,Bi,$i,dr,fr,d0,Nl,c0,f0,Hi=null,Wi=null,Qi,p0,ds,m0,On,Je,Ir,lt,Yi,v0,g0,Ji,hn=-1,_t,ue,ye,Jt,je=null,ma=!1,ci=!1,vn,gn=0,Gl=null,Xl=0,Me,Fe=0,Zt=null,et=1,tt="",ze=null,Ee=null,b=!1,Ke=null,k0,Fn,$d,ql,jl=null,yn=null,Ro=null,Wt=null,pt=!1,$r,Ge,Ar,Rr,H,fi,Al,pi,Gt=0,W=null,G=null,j=null,na=!1,yr=!1,Or=0,w0=0,ra,E0,z0,C0,va,_0,T0,ge=!1,ro,wc,ao,Nc,Sc,Cl=!1,oe=!1,A0,E=null,Ps=!1,te=null,be=!1,D0,la,Jo,Ie,P=0,ee=null,J=null,ne=0,xe=0,wn,X=0,Lr=null,Xt=0,ya=0,Zo=0,wr=null,ve=null,Go=0,An=1/0,qe=null,aa=!1,co=null,xt=null,_l=!1,gt=null,ia=0,Nr=0,fo=null,Dl=-1,Ul=0,Rc,Lc,G0,lr,X0,un,bc,Kc=function(e,t){var n=2<arguments.length&&arguments[2]!==void 0?arguments[2]:null;if(!lu(t))throw Error(w(200));return Y0(e,t,null,n)},Bc=function(e,t){if(!lu(e))throw Error(w(299));var n=!1,r="",l=Lc;return t!==null&&t!==void 0&&(t.unstable_strictMode===!0&&(n=!0),t.identifierPrefix!==void 0&&(r=t.identifierPrefix),t.onRecoverableError!==void 0&&(l=t.onRecoverableError)),t=tu(e,1,!1,null,null,n,!1,r,l),e[lt]=t.current,Fr(e.nodeType===8?e.parentNode:e),new ru(t)},$c=function(e){if(e==null)return null;if(e.nodeType===1)return e;var t=e._reactInternals;if(t===void 0){if(typeof e.render==="function")throw Error(w(188));throw e=Object.keys(e).join(","),Error(w(268,e))}return e=id(t),e=e===null?null:e.stateNode,e},Hc=function(e){return qt(e)},Wc=function(e,t,n){if(!Sa(t))throw Error(w(200));return xa(null,e,t,!0,n)},Vc=function(e,t,n){if(!lu(e))throw Error(w(405));var r=n!=null&&n.hydratedSources||null,l=!1,a="",i=Lc;if(n!==null&&n!==void 0&&(n.unstable_strictMode===!0&&(l=!0),n.identifierPrefix!==void 0&&(a=n.identifierPrefix),n.onRecoverableError!==void 0&&(i=n.onRecoverableError)),t=Uc(t,null,e,1,n!=null?n:null,l,!1,a,i),e[lt]=t.current,Fr(e),r)for(e=0;e<r.length;e++)n=r[e],l=n._getVersion,l=l(n._source),t.mutableSourceEagerHydrationData==null?t.mutableSourceEagerHydrationData=[n,l]:t.mutableSourceEagerHydrationData.push(n,l);return new Na(t)},Qc=function(e,t,n){if(!Sa(t))throw Error(w(200));return xa(null,e,t,!1,n)},Yc=function(e){if(!Sa(e))throw Error(w(40));return e._reactRootContainer?(qt(function(){xa(null,null,e,!1,function(){e._reactRootContainer=null,e[lt]=null})}),!0):!1},Jc,Zc=function(e,t,n,r){if(!Sa(n))throw Error(w(200));if(e==null||e._reactInternals===void 0)throw Error(w(38));return xa(e,t,n,!1,r)},Gc="18.3.1-next-f1338f8080-20240426";var Xc=Af(()=>{Bs=Xe(Lt(),1),K=Xe(Du(),1);$s=new Set,Sr={};rt=!(typeof window>"u"||typeof window.document>"u"||typeof window.document.createElement>"u"),wi=Object.prototype.hasOwnProperty,qp=/^[:A-Z_a-z\u00C0-\u00D6\u00D8-\u00F6\u00F8-\u02FF\u0370-\u037D\u037F-\u1FFF\u200C-\u200D\u2070-\u218F\u2C00-\u2FEF\u3001-\uD7FF\uF900-\uFDCF\uFDF0-\uFFFD][:A-Z_a-z\u00C0-\u00D6\u00D8-\u00F6\u00F8-\u02FF\u0370-\u037D\u037F-\u1FFF\u200C-\u200D\u2070-\u218F\u2C00-\u2FEF\u3001-\uD7FF\uF900-\uFDCF\uFDF0-\uFFFD\-.0-9\u00B7\u0300-\u036F\u203F-\u2040]*$/,Uu={},Lu={};re={};"children dangerouslySetInnerHTML defaultValue defaultChecked innerHTML suppressContentEditableWarning suppressHydrationWarning style".split(" ").forEach(function(e){re[e]=new fe(e,0,!1,e,null,!1,!1)});[["acceptCharset","accept-charset"],["className","class"],["htmlFor","for"],["httpEquiv","http-equiv"]].forEach(function(e){var t=e[0];re[t]=new fe(t,1,!1,e[1],null,!1,!1)});["contentEditable","draggable","spellCheck","value"].forEach(function(e){re[e]=new fe(e,2,!1,e.toLowerCase(),null,!1,!1)});["autoReverse","externalResourcesRequired","focusable","preserveAlpha"].forEach(function(e){re[e]=new fe(e,2,!1,e,null,!1,!1)});"allowFullScreen async autoFocus autoPlay controls default defer disabled disablePictureInPicture disableRemotePlayback formNoValidate hidden loop noModule noValidate open playsInline readOnly required reversed scoped seamless itemScope".split(" ").forEach(function(e){re[e]=new fe(e,3,!1,e.toLowerCase(),null,!1,!1)});["checked","multiple","muted","selected"].forEach(function(e){re[e]=new fe(e,3,!0,e,null,!1,!1)});["capture","download"].forEach(function(e){re[e]=new fe(e,4,!1,e,null,!1,!1)});["cols","rows","size","span"].forEach(function(e){re[e]=new fe(e,6,!1,e,null,!1,!1)});["rowSpan","start"].forEach(function(e){re[e]=new fe(e,5,!1,e.toLowerCase(),null,!1,!1)});ho=/[\-:]([a-z])/g;"accent-height alignment-baseline arabic-form baseline-shift cap-height clip-path clip-rule color-interpolation color-interpolation-filters color-profile color-rendering dominant-baseline enable-background fill-opacity fill-rule flood-color flood-opacity font-family font-size font-size-adjust font-stretch font-style font-variant font-weight glyph-name glyph-orientation-horizontal glyph-orientation-vertical horiz-adv-x horiz-origin-x image-rendering letter-spacing lighting-color marker-end marker-mid marker-start overline-position overline-thickness paint-order panose-1 pointer-events rendering-intent shape-rendering stop-color stop-opacity strikethrough-position strikethrough-thickness stroke-dasharray stroke-dashoffset stroke-linecap stroke-linejoin stroke-miterlimit stroke-opacity stroke-width text-anchor text-decoration text-rendering underline-position underline-thickness unicode-bidi unicode-range units-per-em v-alphabetic v-hanging v-ideographic v-mathematical vector-effect vert-adv-y vert-origin-x vert-origin-y word-spacing writing-mode xmlns:xlink x-height".split(" ").forEach(function(e){var t=e.replace(ho,vo);re[t]=new fe(t,1,!1,e,null,!1,!1)});"xlink:actuate xlink:arcrole xlink:role xlink:show xlink:title xlink:type".split(" ").forEach(function(e){var t=e.replace(ho,vo);re[t]=new fe(t,1,!1,e,"http://www.w3.org/1999/xlink",!1,!1)});["xml:base","xml:lang","xml:space"].forEach(function(e){var t=e.replace(ho,vo);re[t]=new fe(t,1,!1,e,"http://www.w3.org/XML/1998/namespace",!1,!1)});["tabIndex","crossOrigin"].forEach(function(e){re[e]=new fe(e,1,!1,e.toLowerCase(),null,!1,!1)});re.xlinkHref=new fe("xlinkHref",1,!1,"xlink:href","http://www.w3.org/1999/xlink",!0,!1);["src","href","action","formAction"].forEach(function(e){re[e]=new fe(e,1,!1,e.toLowerCase(),null,!0,!0)});ot=Bs.__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED,pl=Symbol.for("react.element"),sn=Symbol.for("react.portal"),dn=Symbol.for("react.fragment"),yo=Symbol.for("react.strict_mode"),Ni=Symbol.for("react.profiler"),Hs=Symbol.for("react.provider"),Ws=Symbol.for("react.context"),ko=Symbol.for("react.forward_ref"),Si=Symbol.for("react.suspense"),xi=Symbol.for("react.suspense_list"),wo=Symbol.for("react.memo"),ft=Symbol.for("react.lazy"),Vs=Symbol.for("react.offscreen"),bu=Symbol.iterator;V=Object.assign;ir=Array.isArray;Xs=function(e){return typeof MSApp<"u"&&MSApp.execUnsafeLocalFunction?function(t,n,r,l){MSApp.execUnsafeLocalFunction(function(){return e(t,n,r,l)})}:e}(function(e,t){if(e.namespaceURI!=="http://www.w3.org/2000/svg"||"innerHTML"in e)e.innerHTML=t;else{hl=hl||document.createElement("div"),hl.innerHTML="<svg>"+t.valueOf().toString()+"</svg>";for(t=hl.firstChild;e.firstChild;)e.removeChild(e.firstChild);for(;t.firstChild;)e.appendChild(t.firstChild)}});pr={animationIterationCount:!0,aspectRatio:!0,borderImageOutset:!0,borderImageSlice:!0,borderImageWidth:!0,boxFlex:!0,boxFlexGroup:!0,boxOrdinalGroup:!0,columnCount:!0,columns:!0,flex:!0,flexGrow:!0,flexPositive:!0,flexShrink:!0,flexNegative:!0,flexOrder:!0,gridArea:!0,gridRow:!0,gridRowEnd:!0,gridRowSpan:!0,gridRowStart:!0,gridColumn:!0,gridColumnEnd:!0,gridColumnSpan:!0,gridColumnStart:!0,fontWeight:!0,lineClamp:!0,lineHeight:!0,opacity:!0,order:!0,orphans:!0,tabSize:!0,widows:!0,zIndex:!0,zoom:!0,fillOpacity:!0,floodOpacity:!0,stopOpacity:!0,strokeDasharray:!0,strokeDashoffset:!0,strokeMiterlimit:!0,strokeOpacity:!0,strokeWidth:!0},am=["Webkit","ms","Moz","O"];Object.keys(pr).forEach(function(e){am.forEach(function(t){t=t+e.charAt(0).toUpperCase()+e.substring(1),pr[t]=pr[e]})});im=V({menuitem:!0},{area:!0,base:!0,br:!0,col:!0,embed:!0,hr:!0,img:!0,input:!0,keygen:!0,link:!0,meta:!0,param:!0,source:!0,track:!0,wbr:!0});if(rt)try{Kt={},Object.defineProperty(Kt,"passive",{get:function(){Ri=!0}}),window.addEventListener("test",Kt,Kt),window.removeEventListener("test",Kt,Kt)}catch(e){Ri=!1}um={onError:function(e){mr=!0,Kl=e}};ud=K.unstable_scheduleCallback,Qu=K.unstable_cancelCallback,fm=K.unstable_shouldYield,pm=K.unstable_requestPaint,Y=K.unstable_now,mm=K.unstable_getCurrentPriorityLevel,So=K.unstable_ImmediatePriority,sd=K.unstable_UserBlockingPriority,$l=K.unstable_NormalPriority,hm=K.unstable_LowPriority,dd=K.unstable_IdlePriority;Be=Math.clz32?Math.clz32:km,gm=Math.log,ym=Math.LN2;yl=[],zr=new Map,Cr=new Map,mt=[],xm="mousedown mouseup touchcancel touchend touchstart auxclick dblclick pointercancel pointerdown pointerup dragend dragstart drop compositionend compositionstart keydown keypress keyup input textInput copy cut paste click change contextmenu reset submit".split(" ");En=ot.ReactCurrentBatchConfig;Rn={eventPhase:0,bubbles:0,cancelable:0,timeStamp:function(e){return e.timeStamp||Date.now()},defaultPrevented:0,isTrusted:0},_o=Ce(Rn),Kr=V({},Rn,{view:0,detail:0}),Tm=Ce(Kr),da=V({},Kr,{screenX:0,screenY:0,clientX:0,clientY:0,pageX:0,pageY:0,ctrlKey:0,shiftKey:0,altKey:0,metaKey:0,getModifierState:To,button:0,buttons:0,relatedTarget:function(e){return e.relatedTarget===void 0?e.fromElement===e.srcElement?e.toElement:e.fromElement:e.relatedTarget},movementX:function(e){if("movementX"in e)return e.movementX;return e!==tr&&(tr&&e.type==="mousemove"?(li=e.screenX-tr.screenX,ai=e.screenY-tr.screenY):ai=li=0,tr=e),li},movementY:function(e){return"movementY"in e?e.movementY:ai}}),Gu=Ce(da),Mm=V({},da,{dataTransfer:0}),Fm=Ce(Mm),Pm=V({},Kr,{relatedTarget:0}),ii=Ce(Pm),Im=V({},Rn,{animationName:0,elapsedTime:0,pseudoElement:0}),Am=Ce(Im),Rm=V({},Rn,{clipboardData:function(e){return"clipboardData"in e?e.clipboardData:window.clipboardData}}),Om=Ce(Rm),Dm=V({},Rn,{data:0}),Xu=Ce(Dm),Um={Esc:"Escape",Spacebar:" ",Left:"ArrowLeft",Up:"ArrowUp",Right:"ArrowRight",Down:"ArrowDown",Del:"Delete",Win:"OS",Menu:"ContextMenu",Apps:"ContextMenu",Scroll:"ScrollLock",MozPrintableKey:"Unidentified"},Lm={8:"Backspace",9:"Tab",12:"Clear",13:"Enter",16:"Shift",17:"Control",18:"Alt",19:"Pause",20:"CapsLock",27:"Escape",32:" ",33:"PageUp",34:"PageDown",35:"End",36:"Home",37:"ArrowLeft",38:"ArrowUp",39:"ArrowRight",40:"ArrowDown",45:"Insert",46:"Delete",112:"F1",113:"F2",114:"F3",115:"F4",116:"F5",117:"F6",118:"F7",119:"F8",120:"F9",121:"F10",122:"F11",123:"F12",144:"NumLock",145:"ScrollLock",224:"Meta"},bm={Alt:"altKey",Control:"ctrlKey",Meta:"metaKey",Shift:"shiftKey"};Bm=V({},Kr,{key:function(e){if(e.key){var t=Um[e.key]||e.key;if(t!=="Unidentified")return t}return e.type==="keypress"?(e=Fl(e),e===13?"Enter":String.fromCharCode(e)):e.type==="keydown"||e.type==="keyup"?Lm[e.keyCode]||"Unidentified":""},code:0,location:0,ctrlKey:0,shiftKey:0,altKey:0,metaKey:0,repeat:0,locale:0,getModifierState:To,charCode:function(e){return e.type==="keypress"?Fl(e):0},keyCode:function(e){return e.type==="keydown"||e.type==="keyup"?e.keyCode:0},which:function(e){return e.type==="keypress"?Fl(e):e.type==="keydown"||e.type==="keyup"?e.keyCode:0}}),$m=Ce(Bm),Hm=V({},da,{pointerId:0,width:0,height:0,pressure:0,tangentialPressure:0,tiltX:0,tiltY:0,twist:0,pointerType:0,isPrimary:0}),qu=Ce(Hm),Wm=V({},Kr,{touches:0,targetTouches:0,changedTouches:0,altKey:0,metaKey:0,ctrlKey:0,shiftKey:0,getModifierState:To}),Vm=Ce(Wm),Qm=V({},Rn,{propertyName:0,elapsedTime:0,pseudoElement:0}),Ym=Ce(Qm),Jm=V({},da,{deltaX:function(e){return"deltaX"in e?e.deltaX:("wheelDeltaX"in e)?-e.wheelDeltaX:0},deltaY:function(e){return"deltaY"in e?e.deltaY:("wheelDeltaY"in e)?-e.wheelDeltaY:("wheelDelta"in e)?-e.wheelDelta:0},deltaZ:0,deltaMode:0}),Zm=Ce(Jm),Gm=[9,13,27,32],Mo=rt&&"CompositionEvent"in window;rt&&"documentMode"in document&&(hr=document.documentMode);Xm=rt&&"TextEvent"in window&&!hr,wd=rt&&(!Mo||hr&&8<hr&&11>=hr),ju=String.fromCharCode(32);e0={color:!0,date:!0,datetime:!0,"datetime-local":!0,email:!0,month:!0,number:!0,password:!0,range:!0,search:!0,tel:!0,text:!0,time:!0,url:!0,week:!0};if(rt){if(rt){if(sr="oninput"in document,!sr)Pl=document.createElement("div"),Pl.setAttribute("oninput","return;"),sr=typeof Pl.oninput==="function";ur=sr}else ur=!1;Ed=ur&&(!document.documentMode||9<document.documentMode)}He=typeof Object.is==="function"?Object.is:o0;s0=rt&&"documentMode"in document&&11>=document.documentMode;pn={animationend:wl("Animation","AnimationEnd"),animationiteration:wl("Animation","AnimationIteration"),animationstart:wl("Animation","AnimationStart"),transitionend:wl("Transition","TransitionEnd")},oi={},Td={};rt&&(Td=document.createElement("div").style,("AnimationEvent"in window)||(delete pn.animationend.animation,delete pn.animationiteration.animation,delete pn.animationstart.animation),("TransitionEvent"in window)||delete pn.transitionend.transition);Md=fa("animationend"),Fd=fa("animationiteration"),Pd=fa("animationstart"),Id=fa("transitionend"),Ad=new Map,is="abort auxClick cancel canPlay canPlayThrough click close contextMenu copy cut drag dragEnd dragEnter dragExit dragLeave dragOver dragStart drop durationChange emptied encrypted ended error gotPointerCapture input invalid keyDown keyPress keyUp load loadedData loadedMetadata loadStart lostPointerCapture mouseDown mouseMove mouseOut mouseOver mouseUp paste pause play playing pointerCancel pointerDown pointerMove pointerOut pointerOver pointerUp progress rateChange reset resize seeked seeking stalled submit suspend timeUpdate touchCancel touchEnd touchStart volumeChange scroll toggle touchMove waiting wheel".split(" ");for(dr=0;dr<is.length;dr++)cr=is[dr],Bi=cr.toLowerCase(),$i=cr[0].toUpperCase()+cr.slice(1),Tt(Bi,"on"+$i);Tt(Md,"onAnimationEnd");Tt(Fd,"onAnimationIteration");Tt(Pd,"onAnimationStart");Tt("dblclick","onDoubleClick");Tt("focusin","onFocus");Tt("focusout","onBlur");Tt(Id,"onTransitionEnd");_n("onMouseEnter",["mouseout","mouseover"]);_n("onMouseLeave",["mouseout","mouseover"]);_n("onPointerEnter",["pointerout","pointerover"]);_n("onPointerLeave",["pointerout","pointerover"]);jt("onChange","change click focusin focusout input keydown keyup selectionchange".split(" "));jt("onSelect","focusout contextmenu dragend focusin keydown keyup mousedown mouseup selectionchange".split(" "));jt("onBeforeInput",["compositionend","keypress","textInput","paste"]);jt("onCompositionEnd","compositionend focusout keydown keypress keyup mousedown".split(" "));jt("onCompositionStart","compositionstart focusout keydown keypress keyup mousedown".split(" "));jt("onCompositionUpdate","compositionupdate focusout keydown keypress keyup mousedown".split(" "));fr="abort canplay canplaythrough durationchange emptied encrypted ended error loadeddata loadedmetadata loadstart pause play playing progress ratechange resize seeked seeking stalled suspend timeupdate volumechange waiting".split(" "),d0=new Set("cancel close invalid load scroll toggle".split(" ").concat(fr));Nl="_reactListening"+Math.random().toString(36).slice(2);c0=/\r\n?/g,f0=/\u0000|\uFFFD/g;Qi=typeof setTimeout==="function"?setTimeout:void 0,p0=typeof clearTimeout==="function"?clearTimeout:void 0,ds=typeof Promise==="function"?Promise:void 0,m0=typeof queueMicrotask==="function"?queueMicrotask:typeof ds<"u"?function(e){return ds.resolve(null).then(e).catch(h0)}:Qi;On=Math.random().toString(36).slice(2),Je="__reactFiber$"+On,Ir="__reactProps$"+On,lt="__reactContainer$"+On,Yi="__reactEvents$"+On,v0="__reactListeners$"+On,g0="__reactHandles$"+On;Ji=[];_t={},ue=Mt(_t),ye=Mt(!1),Jt=_t;vn=[],Me=[];k0=ot.ReactCurrentBatchConfig;Fn=Bd(!0),$d=Bd(!1),ql=Mt(null);$r={},Ge=Mt($r),Ar=Mt($r),Rr=Mt($r);H=Mt(0);fi=[];Al=ot.ReactCurrentDispatcher,pi=ot.ReactCurrentBatchConfig;ra={readContext:Ae,useCallback:ae,useContext:ae,useEffect:ae,useImperativeHandle:ae,useInsertionEffect:ae,useLayoutEffect:ae,useMemo:ae,useReducer:ae,useRef:ae,useState:ae,useDebugValue:ae,useDeferredValue:ae,useTransition:ae,useMutableSource:ae,useSyncExternalStore:ae,useId:ae,unstable_isNewReconciler:!1},E0={readContext:Ae,useCallback:function(e,t){return Ye().memoizedState=[e,t===void 0?null:t],e},useContext:Ae,useEffect:ws,useImperativeHandle:function(e,t,n){return n=n!==null&&n!==void 0?n.concat([e]):null,Rl(4194308,4,nc.bind(null,t,e),n)},useLayoutEffect:function(e,t){return Rl(4194308,4,e,t)},useInsertionEffect:function(e,t){return Rl(4,2,e,t)},useMemo:function(e,t){var n=Ye();return t=t===void 0?null:t,e=e(),n.memoizedState=[e,t],e},useReducer:function(e,t,n){var r=Ye();return t=n!==void 0?n(t):t,r.memoizedState=r.baseState=t,e={pending:null,interleaved:null,lanes:0,dispatch:null,lastRenderedReducer:e,lastRenderedState:t},r.queue=e,e=e.dispatch=S0.bind(null,W,e),[r.memoizedState,e]},useRef:function(e){var t=Ye();return e={current:e},t.memoizedState=e},useState:ks,useDebugValue:Qo,useDeferredValue:function(e){return Ye().memoizedState=e},useTransition:function(){var e=ks(!1),t=e[0];return e=N0.bind(null,e[1]),Ye().memoizedState=e,[t,e]},useMutableSource:function(){},useSyncExternalStore:function(e,t,n){var r=W,l=Ye();if(b){if(n===void 0)throw Error(w(407));n=n()}else{if(n=t(),ee===null)throw Error(w(349));(Gt&30)!==0||Jd(r,t,n)}l.memoizedState=n;var a={value:n,getSnapshot:t};return l.queue=a,ws(Gd.bind(null,r,a,e),[e]),r.flags|=2048,Ur(9,Zd.bind(null,r,a,n,t),void 0,null),n},useId:function(){var e=Ye(),t=ee.identifierPrefix;if(b){var n=tt,r=et;n=(r&~(1<<32-Be(r)-1)).toString(32)+n,t=":"+t+"R"+n,n=Or++,0<n&&(t+="H"+n.toString(32)),t+=":"}else n=w0++,t=":"+t+"r"+n.toString(32)+":";return e.memoizedState=t},unstable_isNewReconciler:!1},z0={readContext:Ae,useCallback:lc,useContext:Ae,useEffect:Vo,useImperativeHandle:rc,useInsertionEffect:ec,useLayoutEffect:tc,useMemo:ac,useReducer:mi,useRef:jd,useState:function(){return mi(Dr)},useDebugValue:Qo,useDeferredValue:function(e){var t=Re();return ic(t,G.memoizedState,e)},useTransition:function(){var e=mi(Dr)[0],t=Re().memoizedState;return[e,t]},useMutableSource:Qd,useSyncExternalStore:Yd,useId:oc,unstable_isNewReconciler:!1},C0={readContext:Ae,useCallback:lc,useContext:Ae,useEffect:Vo,useImperativeHandle:rc,useInsertionEffect:ec,useLayoutEffect:tc,useMemo:ac,useReducer:hi,useRef:jd,useState:function(){return hi(Dr)},useDebugValue:Qo,useDeferredValue:function(e){var t=Re();return G===null?t.memoizedState=e:ic(t,G.memoizedState,e)},useTransition:function(){var e=hi(Dr)[0],t=Re().memoizedState;return[e,t]},useMutableSource:Qd,useSyncExternalStore:Yd,useId:oc,unstable_isNewReconciler:!1};va={isMounted:function(e){return(e=e._reactInternals)?en(e)===e:!1},enqueueSetState:function(e,t,n){e=e._reactInternals;var r=ce(),l=Et(e),a=nt(r,l);a.payload=t,n!==void 0&&n!==null&&(a.callback=n),t=St(e,a,l),t!==null&&($e(t,e,l,r),Il(t,e,l))},enqueueReplaceState:function(e,t,n){e=e._reactInternals;var r=ce(),l=Et(e),a=nt(r,l);a.tag=1,a.payload=t,n!==void 0&&n!==null&&(a.callback=n),t=St(e,a,l),t!==null&&($e(t,e,l,r),Il(t,e,l))},enqueueForceUpdate:function(e,t){e=e._reactInternals;var n=ce(),r=Et(e),l=nt(n,r);l.tag=2,t!==void 0&&t!==null&&(l.callback=t),t=St(e,l,r),t!==null&&($e(t,e,r,n),Il(t,e,r))}};_0=typeof WeakMap==="function"?WeakMap:Map;T0=ot.ReactCurrentOwner;ro={dehydrated:null,treeContext:null,retryLane:0};wc=function(e,t){for(var n=t.child;n!==null;){if(n.tag===5||n.tag===6)e.appendChild(n.stateNode);else if(n.tag!==4&&n.child!==null){n.child.return=n,n=n.child;continue}if(n===t)break;for(;n.sibling===null;){if(n.return===null||n.return===t)return;n=n.return}n.sibling.return=n.return,n=n.sibling}};ao=function(){};Nc=function(e,t,n,r){var l=e.memoizedProps;if(l!==r){e=t.stateNode,Vt(Ge.current);var a=null;switch(n){case"input":l=zi(e,l),r=zi(e,r),a=[];break;case"select":l=V({},l,{value:void 0}),r=V({},r,{value:void 0}),a=[];break;case"textarea":l=Ti(e,l),r=Ti(e,r),a=[];break;default:typeof l.onClick!=="function"&&typeof r.onClick==="function"&&(e.onclick=Yl)}Fi(n,r);var i;n=null;for(f in l)if(!r.hasOwnProperty(f)&&l.hasOwnProperty(f)&&l[f]!=null)if(f==="style"){var o=l[f];for(i in o)o.hasOwnProperty(i)&&(n||(n={}),n[i]="")}else f!=="dangerouslySetInnerHTML"&&f!=="children"&&f!=="suppressContentEditableWarning"&&f!=="suppressHydrationWarning"&&f!=="autoFocus"&&(Sr.hasOwnProperty(f)?a||(a=[]):(a=a||[]).push(f,null));for(f in r){var u=r[f];if(o=l!=null?l[f]:void 0,r.hasOwnProperty(f)&&u!==o&&(u!=null||o!=null))if(f==="style")if(o){for(i in o)!o.hasOwnProperty(i)||u&&u.hasOwnProperty(i)||(n||(n={}),n[i]="");for(i in u)u.hasOwnProperty(i)&&o[i]!==u[i]&&(n||(n={}),n[i]=u[i])}else n||(a||(a=[]),a.push(f,n)),n=u;else f==="dangerouslySetInnerHTML"?(u=u?u.__html:void 0,o=o?o.__html:void 0,u!=null&&o!==u&&(a=a||[]).push(f,u)):f==="children"?typeof u!=="string"&&typeof u!=="number"||(a=a||[]).push(f,""+u):f!=="suppressContentEditableWarning"&&f!=="suppressHydrationWarning"&&(Sr.hasOwnProperty(f)?(u!=null&&f==="onScroll"&&U("scroll",e),a||o===u||(a=[])):(a=a||[]).push(f,u))}n&&(a=a||[]).push("style",n);var f=a;if(t.updateQueue=f)t.flags|=4}};Sc=function(e,t,n,r){n!==r&&(t.flags|=4)};A0=typeof WeakSet==="function"?WeakSet:Set;D0=Math.ceil,la=ot.ReactCurrentDispatcher,Jo=ot.ReactCurrentOwner,Ie=ot.ReactCurrentBatchConfig,wn=Mt(0);Rc=function(e,t,n){if(e!==null)if(e.memoizedProps!==t.pendingProps||ye.current)ge=!0;else{if((e.lanes&n)===0&&(t.flags&128)===0)return ge=!1,F0(e,t,n);ge=(e.flags&131072)!==0?!0:!1}else ge=!1,b&&(t.flags&1048576)!==0&&Ld(t,Xl,t.index);switch(t.lanes=0,t.tag){case 2:var r=t.type;Ol(e,t),e=t.pendingProps;var l=Tn(t,ue.current);zn(t,n),l=Ho(null,t,r,e,l,n);var a=Wo();return t.flags|=1,typeof l==="object"&&l!==null&&typeof l.render==="function"&&l.$$typeof===void 0?(t.tag=1,t.memoizedState=null,t.updateQueue=null,ke(r)?(a=!0,Zl(t)):a=!1,t.memoizedState=l.state!==null&&l.state!==void 0?l.state:null,Lo(t),l.updater=va,t.stateNode=l,l._reactInternals=t,ji(t,r,e,n),t=no(null,t,r,!0,a,n)):(t.tag=0,b&&a&&Po(t),de(null,t,l,n),t=t.child),t;case 16:r=t.elementType;e:{switch(Ol(e,t),e=t.pendingProps,l=r._init,r=l(r._payload),t.type=r,l=t.tag=V0(r),e=Le(r,e),l){case 0:t=to(null,t,r,e,n);break e;case 1:t=Ts(null,t,r,e,n);break e;case 11:t=Cs(null,t,r,e,n);break e;case 14:t=_s(null,t,r,Le(r.type,e),n);break e}throw Error(w(306,r,""))}return t;case 0:return r=t.type,l=t.pendingProps,l=t.elementType===r?l:Le(r,l),to(e,t,r,l,n);case 1:return r=t.type,l=t.pendingProps,l=t.elementType===r?l:Le(r,l),Ts(e,t,r,l,n);case 3:e:{if(gc(t),e===null)throw Error(w(387));r=t.pendingProps,a=t.memoizedState,l=a.element,Wd(e,t),ea(t,r,null,n);var i=t.memoizedState;if(r=i.element,a.isDehydrated)if(a={element:r,isDehydrated:!1,cache:i.cache,pendingSuspenseBoundaries:i.pendingSuspenseBoundaries,transitions:i.transitions},t.updateQueue.baseState=a,t.memoizedState=a,t.flags&256){l=In(Error(w(423)),t),t=Ms(e,t,r,n,l);break e}else if(r!==l){l=In(Error(w(424)),t),t=Ms(e,t,r,n,l);break e}else for(Ee=Nt(t.stateNode.containerInfo.firstChild),ze=t,b=!0,Ke=null,n=$d(t,null,r,n),t.child=n;n;)n.flags=n.flags&-3|4096,n=n.sibling;else{if(Mn(),r===l){t=it(e,t,n);break e}de(e,t,r,n)}t=t.child}return t;case 5:return Vd(t),e===null&&Gi(t),r=t.type,l=t.pendingProps,a=e!==null?e.memoizedProps:null,i=l.children,Vi(r,l)?i=null:a!==null&&Vi(r,a)&&(t.flags|=32),vc(e,t),de(e,t,i,n),t.child;case 6:return e===null&&Gi(t),null;case 13:return yc(e,t,n);case 4:return bo(t,t.stateNode.containerInfo),r=t.pendingProps,e===null?t.child=Fn(t,null,r,n):de(e,t,r,n),t.child;case 11:return r=t.type,l=t.pendingProps,l=t.elementType===r?l:Le(r,l),Cs(e,t,r,l,n);case 7:return de(e,t,t.pendingProps,n),t.child;case 8:return de(e,t,t.pendingProps.children,n),t.child;case 12:return de(e,t,t.pendingProps.children,n),t.child;case 10:e:{if(r=t.type._context,l=t.pendingProps,a=t.memoizedProps,i=l.value,D(ql,r._currentValue),r._currentValue=i,a!==null)if(He(a.value,i)){if(a.children===l.children&&!ye.current){t=it(e,t,n);break e}}else for(a=t.child,a!==null&&(a.return=t);a!==null;){var o=a.dependencies;if(o!==null){i=a.child;for(var u=o.firstContext;u!==null;){if(u.context===r){if(a.tag===1){u=nt(-1,n&-n),u.tag=2;var f=a.updateQueue;if(f!==null){f=f.shared;var h=f.pending;h===null?u.next=u:(u.next=h.next,h.next=u),f.pending=u}}a.lanes|=n,u=a.alternate,u!==null&&(u.lanes|=n),Xi(a.return,n,t),o.lanes|=n;break}u=u.next}}else if(a.tag===10)i=a.type===t.type?null:a.child;else if(a.tag===18){if(i=a.return,i===null)throw Error(w(341));i.lanes|=n,o=i.alternate,o!==null&&(o.lanes|=n),Xi(i,n,t),i=a.sibling}else i=a.child;if(i!==null)i.return=a;else for(i=a;i!==null;){if(i===t){i=null;break}if(a=i.sibling,a!==null){a.return=i.return,i=a;break}i=i.return}a=i}de(e,t,l.children,n),t=t.child}return t;case 9:return l=t.type,r=t.pendingProps.children,zn(t,n),l=Ae(l),r=r(l),t.flags|=1,de(e,t,r,n),t.child;case 14:return r=t.type,l=Le(r,t.pendingProps),l=Le(r.type,l),_s(e,t,r,l,n);case 15:return mc(e,t,t.type,t.pendingProps,n);case 17:return r=t.type,l=t.pendingProps,l=t.elementType===r?l:Le(r,l),Ol(e,t),t.tag=1,ke(r)?(e=!0,Zl(t)):e=!1,zn(t,n),cc(t,r,l),ji(t,r,l,n),no(null,t,r,!0,e,n);case 19:return kc(e,t,n);case 22:return hc(e,t,n)}throw Error(w(156,t.tag))};Lc=typeof reportError==="function"?reportError:function(e){console.error(e)};Na.prototype.render=ru.prototype.render=function(e){var t=this._internalRoot;if(t===null)throw Error(w(409));wa(e,t,null,null)};Na.prototype.unmount=ru.prototype.unmount=function(){var e=this._internalRoot;if(e!==null){this._internalRoot=null;var t=e.containerInfo;qt(function(){wa(null,e,null,null)}),t[lt]=null}};Na.prototype.unstable_scheduleHydration=function(e){if(e){var t=hd();e={blockedOn:null,target:e,priority:t};for(var n=0;n<mt.length&&t!==0&&t<mt[n].priority;n++);mt.splice(n,0,e),n===0&&gd(e)}};pd=function(e){switch(e.tag){case 3:var t=e.stateNode;if(t.current.memoizedState.isDehydrated){var n=or(t.pendingLanes);n!==0&&(xo(t,n|1),we(t,Y()),(P&6)===0&&(An=Y()+500,Ft()))}break;case 13:qt(function(){var r=at(e,1);if(r!==null){var l=ce();$e(r,e,1,l)}}),nu(e,1)}};Eo=function(e){if(e.tag===13){var t=at(e,134217728);if(t!==null){var n=ce();$e(t,e,134217728,n)}nu(e,134217728)}};md=function(e){if(e.tag===13){var t=Et(e),n=at(e,t);if(n!==null){var r=ce();$e(n,e,t,r)}nu(e,t)}};hd=function(){return O};vd=function(e,t){var n=O;try{return O=e,t()}finally{O=n}};Ai=function(e,t,n){switch(t){case"input":if(Ci(e,n),t=n.name,n.type==="radio"&&t!=null){for(n=e;n.parentNode;)n=n.parentNode;n=n.querySelectorAll("input[name="+JSON.stringify(""+t)+'][type="radio"]');for(t=0;t<n.length;t++){var r=n[t];if(r!==e&&r.form===e.form){var l=pa(r);if(!l)throw Error(w(90));Ys(r),Ci(r,l)}}}break;case"textarea":Zs(e,n);break;case"select":t=n.value,t!=null&&Nn(e,!!n.multiple,t,!1)}};nd=Xo;rd=qt;G0={usingClientEntryPoint:!1,Events:[Br,mn,pa,ed,td,Xo]},lr={findFiberByHostInstance:Ht,bundleType:0,version:"18.3.1",rendererPackageName:"react-dom"},X0={bundleType:lr.bundleType,version:lr.version,rendererPackageName:lr.rendererPackageName,rendererConfig:lr.rendererConfig,overrideHookState:null,overrideHookStateDeletePath:null,overrideHookStateRenamePath:null,overrideProps:null,overridePropsDeletePath:null,overridePropsRenamePath:null,setErrorHandler:null,setSuspenseHandler:null,scheduleUpdate:null,currentDispatcherRef:ot.ReactCurrentDispatcher,findHostInstanceByFiber:function(e){return e=id(e),e===null?null:e.stateNode},findFiberByHostInstance:lr.findFiberByHostInstance||J0,findHostInstancesForRefresh:null,scheduleRefresh:null,scheduleRoot:null,setRefreshHandler:null,getCurrentFiber:null,reconcilerVersion:"18.3.1-next-f1338f8080-20240426"};if(typeof __REACT_DEVTOOLS_GLOBAL_HOOK__<"u"){if(un=__REACT_DEVTOOLS_GLOBAL_HOOK__,!un.isDisabled&&un.supportsFiber)try{sa=un.inject(X0),Ze=un}catch(e){}}bc=G0,Jc=Xo});var ef=nl((sh,jc)=>{Xc();function qc(){if(typeof __REACT_DEVTOOLS_GLOBAL_HOOK__>"u"||typeof __REACT_DEVTOOLS_GLOBAL_HOOK__.checkDCE!=="function")return;try{__REACT_DEVTOOLS_GLOBAL_HOOK__.checkDCE(qc)}catch(e){console.error(e)}}qc(),jc.exports=au});var tf=nl((j0)=>{var Hr=Xe(ef(),1);j0.createRoot=Hr.createRoot,j0.hydrateRoot=Hr.hydrateRoot;var q0});var uf=Xe(Lt(),1),sf=Xe(tf(),1);var F=Xe(Lt(),1);var za=Xe(Lt(),1);var nf=(e)=>e.replace(/([a-z0-9])([A-Z])/g,"$1-$2").toLowerCase(),Ea=(...e)=>e.filter((t,n,r)=>{return Boolean(t)&&t.trim()!==""&&r.indexOf(t)===n}).join(" ").trim();var Wr=Xe(Lt(),1);var rf={xmlns:"http://www.w3.org/2000/svg",width:24,height:24,viewBox:"0 0 24 24",fill:"none",stroke:"currentColor",strokeWidth:2,strokeLinecap:"round",strokeLinejoin:"round"};var lf=Wr.forwardRef(({color:e="currentColor",size:t=24,strokeWidth:n=2,absoluteStrokeWidth:r,className:l="",children:a,iconNode:i,...o},u)=>{return Wr.createElement("svg",{ref:u,...rf,width:t,height:t,stroke:e,strokeWidth:r?Number(n)*24/Number(t):n,className:Ea("lucide",l),...o},[...i.map(([f,h])=>Wr.createElement(f,h)),...Array.isArray(a)?a:[a]])});var I=(e,t)=>{let n=za.forwardRef(({className:r,...l},a)=>za.createElement(lf,{ref:a,iconNode:t,className:Ea(`lucide-${nf(e)}`,r),...l}));return n.displayName=`${e}`,n};var Vr=I("AlarmClock",[["circle",{cx:"12",cy:"13",r:"8",key:"3y4lt7"}],["path",{d:"M12 9v4l2 2",key:"1c63tq"}],["path",{d:"M5 3 2 6",key:"18tl5t"}],["path",{d:"m22 6-3-3",key:"1opdir"}],["path",{d:"M6.38 18.7 4 21",key:"17xu3x"}],["path",{d:"M17.64 18.67 20 21",key:"kv2oe2"}]]);var Pt=I("BadgeCheck",[["path",{d:"M3.85 8.62a4 4 0 0 1 4.78-4.77 4 4 0 0 1 6.74 0 4 4 0 0 1 4.78 4.78 4 4 0 0 1 0 6.74 4 4 0 0 1-4.77 4.78 4 4 0 0 1-6.75 0 4 4 0 0 1-4.78-4.77 4 4 0 0 1 0-6.76Z",key:"3c2336"}],["path",{d:"m9 12 2 2 4-4",key:"dzmm74"}]]);var Dn=I("Bell",[["path",{d:"M10.268 21a2 2 0 0 0 3.464 0",key:"vwvbt9"}],["path",{d:"M3.262 15.326A1 1 0 0 0 4 17h16a1 1 0 0 0 .74-1.673C19.41 13.956 18 12.499 18 8A6 6 0 0 0 6 8c0 4.499-1.411 5.956-2.738 7.326",key:"11g9vi"}]]);var Qr=I("CalendarDays",[["path",{d:"M8 2v4",key:"1cmpym"}],["path",{d:"M16 2v4",key:"4m81vk"}],["rect",{width:"18",height:"18",x:"3",y:"4",rx:"2",key:"1hopcy"}],["path",{d:"M3 10h18",key:"8toen8"}],["path",{d:"M8 14h.01",key:"6423bh"}],["path",{d:"M12 14h.01",key:"1etili"}],["path",{d:"M16 14h.01",key:"1gbofw"}],["path",{d:"M8 18h.01",key:"lrp35t"}],["path",{d:"M12 18h.01",key:"mhygvu"}],["path",{d:"M16 18h.01",key:"kzsmim"}]]);var ut=I("CircleCheck",[["circle",{cx:"12",cy:"12",r:"10",key:"1mglay"}],["path",{d:"m9 12 2 2 4-4",key:"dzmm74"}]]);var Un=I("ClipboardCheck",[["rect",{width:"8",height:"4",x:"8",y:"2",rx:"1",ry:"1",key:"tgr4d6"}],["path",{d:"M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2",key:"116196"}],["path",{d:"m9 14 2 2 4-4",key:"df797q"}]]);var Yr=I("Clock3",[["circle",{cx:"12",cy:"12",r:"10",key:"1mglay"}],["polyline",{points:"12 6 12 12 16.5 12",key:"1aq6pp"}]]);var Jr=I("FileText",[["path",{d:"M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7Z",key:"1rqfz7"}],["path",{d:"M14 2v4a2 2 0 0 0 2 2h4",key:"tnqrlb"}],["path",{d:"M10 9H8",key:"b1mrlr"}],["path",{d:"M16 13H8",key:"t4e002"}],["path",{d:"M16 17H8",key:"z1uh3a"}]]);var It=I("House",[["path",{d:"M15 21v-8a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1v8",key:"5wwlr5"}],["path",{d:"M3 10a2 2 0 0 1 .709-1.528l7-5.999a2 2 0 0 1 2.582 0l7 5.999A2 2 0 0 1 21 10v9a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z",key:"1d0kgt"}]]);var At=I("Lock",[["rect",{width:"18",height:"11",x:"3",y:"11",rx:"2",ry:"2",key:"1w4ew1"}],["path",{d:"M7 11V7a5 5 0 0 1 10 0v4",key:"fwvmzm"}]]);var tn=I("ShieldAlert",[["path",{d:"M20 13c0 5-3.5 7.5-7.66 8.95a1 1 0 0 1-.67-.01C7.5 20.5 4 18 4 13V6a1 1 0 0 1 1-1c2 0 4.5-1.2 6.24-2.72a1.17 1.17 0 0 1 1.52 0C14.51 3.81 17 5 19 5a1 1 0 0 1 1 1z",key:"oel41y"}],["path",{d:"M12 8v4",key:"1got3b"}],["path",{d:"M12 16h.01",key:"1drbdi"}]]);var Rt=I("Sparkles",[["path",{d:"M9.937 15.5A2 2 0 0 0 8.5 14.063l-6.135-1.582a.5.5 0 0 1 0-.962L8.5 9.936A2 2 0 0 0 9.937 8.5l1.582-6.135a.5.5 0 0 1 .963 0L14.063 8.5A2 2 0 0 0 15.5 9.937l6.135 1.581a.5.5 0 0 1 0 .964L15.5 14.063a2 2 0 0 0-1.437 1.437l-1.582 6.135a.5.5 0 0 1-.963 0z",key:"4pj2yx"}],["path",{d:"M20 3v4",key:"1olli1"}],["path",{d:"M22 5h-4",key:"1gvqau"}],["path",{d:"M4 17v2",key:"vumght"}],["path",{d:"M5 18H3",key:"zchphs"}]]);var nn=I("Volume2",[["path",{d:"M11 4.702a.705.705 0 0 0-1.203-.498L6.413 7.587A1.4 1.4 0 0 1 5.416 8H3a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h2.416a1.4 1.4 0 0 1 .997.413l3.383 3.384A.705.705 0 0 0 11 19.298z",key:"uqj9uw"}],["path",{d:"M16 9a5 5 0 0 1 0 6",key:"1q6k2b"}],["path",{d:"M19.364 18.364a9 9 0 0 0 0-12.728",key:"ijwkga"}]]);var Zr=I("VolumeX",[["path",{d:"M11 4.702a.705.705 0 0 0-1.203-.498L6.413 7.587A1.4 1.4 0 0 1 5.416 8H3a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h2.416a1.4 1.4 0 0 1 .997.413l3.383 3.384A.705.705 0 0 0 11 19.298z",key:"uqj9uw"}],["line",{x1:"22",x2:"16",y1:"9",y2:"15",key:"1ewh16"}],["line",{x1:"16",x2:"22",y1:"9",y2:"15",key:"5ykzw1"}]]);var Ln=I("Wallet",[["path",{d:"M19 7V4a1 1 0 0 0-1-1H5a2 2 0 0 0 0 4h15a1 1 0 0 1 1 1v4h-3a2 2 0 0 0 0 4h3a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1",key:"18etb6"}],["path",{d:"M3 5v14a2 2 0 0 0 2 2h15a1 1 0 0 0 1-1v-4",key:"xoc0q4"}]]);var bn=I("X",[["path",{d:"M18 6 6 18",key:"1bl5f8"}],["path",{d:"m6 6 12 12",key:"d8bk6v"}]]);var af=Xe(Lt(),1),eh=Symbol.for("react.element"),th=Symbol.for("react.fragment"),nh=Object.prototype.hasOwnProperty,rh=af.__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED.ReactCurrentOwner,lh={key:!0,ref:!0,__self:!0,__source:!0};function of(e,t,n){var r,l={},a=null,i=null;n!==void 0&&(a=""+n),t.key!==void 0&&(a=""+t.key),t.ref!==void 0&&(i=t.ref);for(r in t)nh.call(t,r)&&!lh.hasOwnProperty(r)&&(l[r]=t[r]);if(e&&e.defaultProps)for(r in t=e.defaultProps,t)l[r]===void 0&&(l[r]=t[r]);return{$$typeof:eh,type:e,key:a,ref:i,props:l,_owner:rh.current}}var Ot=th,s=of,d=of;var _a=[{section:"SEHEMU 1 — USAFI",items:["Usafi wa choo","Kuweka maji chooni","Kusafisha uwanja wa nje na vyoo vya nje","Kusafisha vyoo vya ndani - kufuta ndani vyoo vyote","Kufuta masofa yote - kuyakung'uta sofa na viti na vumbi","Kudeki sakafu","Kufua nguo chafu zilizokaa siku 2-3","Kuhakikisha hakuna nguo chafu"]},{section:"SEHEMU 2 — MPANGILIO",items:["Kupanga laptop na kompyuta, kusafisha meza na waya mpangilio mzuri","Kupangilia meza na viti vya wateja vizuri","Kuhakikisha vitu havionekani lafu lafu","Kutandika kitanda cha wagonjwa na kuhakikisha kimewekwa shuka vizuri"]},{section:"SEHEMU 3 — VIFAA & MAJI",items:["Kufuta dawa na kuzipanga kwenye shelf vizuri","Kuweka maji safi kwenye filter ya maji ya kunywa","Kuifuta distiller","Kufuta kompyuta, laptop na simu","Kufuta printer na vifaa vyote vya electronics","Kufuta feni vumbi","Kufuta kabati vumbi na TV na vitu vingine","Kutoa vumbi vifaa vyote - printer, remote hakuna vumbi","Kufuatilia spika ni safi, zimefutwa vizuri, hazina vumbi","Kufuatilia spika za matangazo zimepelekwa kwa matangazo"]},{section:"SEHEMU 4 — WAGONJWA & RIPOTI",items:["Kufuatilia orodha ya wagonjwa wanaotumia dawa","Kuweka ripoti kila baada ya siku 2-3","Kuandaa ripoti ya mauzo kila siku na taarifa za ofisi kuikabidhi kwa Mkurugenzi - hata kama hakuna mauzo"]},{section:"SEHEMU 5 — MITANDAO",items:["Kuweka status kwenye simu ya ofisi","Kufuatilia ujumbe usiojibiwa SMS na WhatsApp","Kufuatilia ujumbe usiojibiwa TikTok, Facebook, Instagram","Kufuatilia posti 2 mpya kila siku kwa kila mtandao zimeandaliwa","Kufuatilia comment zote zimejibiwa na message zote","Kufuatilia uandaaji wa maudhui na mawazo ya masomo, kuedit na kuhakikisha hakuna makosa"]},{section:"SEHEMU 6 — MUDA & DAKTARI",items:["Kufuatilia saa 12:00 na 15:00 kufuliwa na kudekiwa tena","Kufuatilia daktari amevaa kiofisa na kiheshima","Kuhakikisha daktari amekunywa chai / chai ipo kwa wafanyakazi","Kufuatilia magari ya ofisi mawili ni safi na salama","Kufuatilia uchafu wa kuchomwa umechomwa na wa kutupwa umetupwa","Kufuatilia maji ya akiba yametunzwa","Kufuatilia chakula cha mchana kwa daktari"]},{section:"SEHEMU 7 — KUKUZA KLINIKI & KUREJESHA WATEJA",gold:!0,note:"Wateja waliopotea sababu kubwa ni kutokufuatilia - sasa kila siku tunawafuatilia.",items:["Kuwapigia wateja 5 waliopotea leo - kuuliza sababu, kuwaomba radhi na ofa ya kurudi","Kufuatilia wateja walioweka appointment hawakufika - kuwakumbusha na kupanga upya","Kuomba review kwa wateja 3 walioridhika na kuweka kwenye status","Kuandika orodha ya wateja wa zamani na kuwatumia shukrani + ofa","Kutoa huduma ya ziada - kukaribisha, maji/chai, kuongea vizuri, Asante","Kurekodi malalamiko na kuyapeleka kwa Mkurugenzi siku hiyo na kufuatilia yametatuliwa","Kufuatilia wateja baada ya siku 2-3 kuuliza wanaendeleaje","Kuandaa ofa ya wiki na kuisambaza WhatsApp/status","Kuhakikisha bei na huduma zimeandikwa wazi","Kujifunza kitu kipya kila siku kuhusu huduma bora - kusoma ukurasa 1 wa mwongozo"]}],Ca=_a.flatMap((e,t)=>e.items.map((n,r)=>({num:_a.slice(0,t).reduce((l,a)=>l+a.items.length,0)+r+1,title:n,section:e.section,gold:!!e.gold}))),ah=["Fika kazini kabla ya 07:30 na fanya Sign In mara moja.","Kamilisha majukumu yote 48 kila siku — hakuna la kuruka.","Usijaze jukumu ambalo hukutekeleza kweli. Udanganyifu ni kosa kubwa.","Weka usafi, mpangilio na heshima mbele kila wakati.","Heshimu wagonjwa, wateja na Mkurugenzi. Ongea vizuri na kwa upole.","Tunza vifaa, dawa, maji na mali za kliniki kwa uaminifu.","Jibu ujumbe, comment na simu za wateja kwa wakati.","Andaa ripoti sahihi kila siku na ikabidhi kwa Mkurugenzi.","Fuatilia wateja waliopotea, waliokosa appointment na malalamiko yao.","Vaa kiofisa na kiheshima. Kuwa mfano mzuri wa kliniki.","Usitumie simu binafsi wakati wa kazi isipokuwa kwa kazi ya ofisi.","Tunzwa siri za wagonjwa na taarifa za kliniki.","Ripoti tatizo, uharibifu au hatari mara moja kwa Mkurugenzi.","Shirikiana na wenzako. Kazi ya timu ndiyo mafanikio ya kliniki.","Jifunze kila siku. Huduma bora ndiyo inawafanya wateja warudi."],A=(e)=>new Intl.NumberFormat("sw-TZ",{maximumFractionDigits:0}).format(Math.round(e)),Gr=(e)=>e.toLocaleTimeString("sw-TZ",{hour:"2-digit",minute:"2-digit",second:"2-digit"});function iu(){let[e,t]=F.useState(new Date),[n,r]=F.useState("Dashboard"),[l,a]=F.useState(null),[i,o]=F.useState({name:"",id:"",role:"Msaidizi wa Ofisi",salary:""}),[u,f]=F.useState(""),[h,g]=F.useState(""),[v,S]=F.useState(""),[N,x]=F.useState({}),[R,p]=F.useState(!1),[c,m]=F.useState(""),[k,z]=F.useState(""),[C,_]=F.useState(null),[T,B]=F.useState(null),[M,Ne]=F.useState(null),[Kn,ou]=F.useState(!1),[df,Bn]=F.useState(!1),[cf,Ta]=F.useState(!1),[ff,pf]=F.useState(!1),[uu,mf]=F.useState(""),[rn,su]=F.useState(10),[Xr,Ma]=F.useState(!1),[$n,hf]=F.useState(!0),[du,Hn]=F.useState(600),[cu,Wn]=F.useState(""),[vf,fu]=F.useState(!1),[pu,mu]=F.useState([]),[qr,q]=F.useState(""),Fa=F.useRef(!1),Z=Object.keys(N).length,jr=48-Z,pe=Math.round(Z/48*100),el=l?.salary||0,Dt=el/30,tl=Dt/48,me=Z*tl,Ut=Dt-me,We=Ca.find((y)=>!N[y.num]);F.useEffect(()=>{let y=setInterval(()=>t(new Date),1000);return()=>clearInterval(y)},[]),F.useEffect(()=>{if(qr){let y=setTimeout(()=>q(""),4200);return()=>clearTimeout(y)}},[qr]);let Vn=(y)=>{if(!$n)return;try{window.speechSynthesis.cancel();let $=new SpeechSynthesisUtterance(y);$.lang="sw-TZ",$.rate=0.92,window.speechSynthesis.speak($)}catch{}},Pa=(y=3)=>{if(!$n)return;try{let Se=new(window.AudioContext||window.webkitAudioContext);for(let st=0;st<y;st++){let Oe=Se.createOscillator(),he=Se.createGain();Oe.connect(he),he.connect(Se.destination),Oe.frequency.value=880,Oe.type="sine";let _e=Se.currentTime+st*0.35;he.gain.setValueAtTime(0.0001,_e),he.gain.exponentialRampToValueAtTime(0.5,_e+0.02),he.gain.exponentialRampToValueAtTime(0.0001,_e+0.28),Oe.start(_e),Oe.stop(_e+0.3)}}catch{}};F.useEffect(()=>{let y=e.getHours()*60+e.getMinutes();if(y===450&&!c&&!Fa.current)Fa.current=!0,Pa(3),Vn("Muda wa kuanza kazi umefika. Tafadhali fanya Sign In sasa."),Wn("Muda wa kuanza kazi umefika — fanya Sign In sasa.");if(y>451)Fa.current=!1},[e,c]),F.useEffect(()=>{if(!Xr||R)return;let y=setInterval(()=>{Hn(($)=>{if($<=1){if(We)Pa(3),Vn(`Tafadhali tika jukumu namba ${We.num}. Jukumu namba ${We.num} limefatwa bado halijakamilika. Jukumu ni ${We.title}.`),Wn(`Jukumu namba ${We.num} bado halijakamilika — tika sasa!`);return rn*60}return $-1})},1000);return()=>clearInterval(y)},[Xr,rn,R,We?.num]);let Qn=e.toLocaleDateString("sw-TZ",{weekday:"long",day:"numeric",month:"long",year:"numeric"}),Yn=new Date;Yn.setHours(7,30,0,0);let Ia=new Date;Ia.setHours(17,0,0,0);let Aa=Math.max(0,Math.floor((Yn.getTime()-e.getTime())/1000)),hu=C?(T||e).getTime()-C.getTime():0,Ra=Math.floor(hu/3600000),Oa=Math.floor(hu%3600000/60000),gf=C?C.getTime()>Yn.getTime():e.getTime()>Yn.getTime()&&!C,vu=pe<50?"#EF4444":pe<90?"#F59E0B":"#10B981",gu=2*Math.PI*78,yf=(y)=>{let $=y.target.files?.[0];if(!$)return;let Se=new FileReader;Se.onload=()=>f(String(Se.result)),Se.readAsDataURL($)},kf=(y)=>{if(y.preventDefault(),!i.name.trim()||!i.id.trim()||!i.salary){g("Tafadhali jaza jina, ID na mshahara.");return}if(!u){g("Tafadhali pakia picha yako kwanza.");return}a({name:i.name.trim(),id:i.id.trim(),role:i.role,salary:Number(i.salary),photo:u}),g(""),q(`Karibu, ${i.name.trim()}! Usajili umekamilika — anza kazi sasa.`),r("Dashboard")},wf=()=>{if(v.trim().toUpperCase()!=="FUTA"){q("Andika FUTA kwa herufi kubwa ili kuthibitisha.");return}a(null),o({name:"",id:"",role:"Msaidizi wa Ofisi",salary:""}),f(""),S(""),x({}),p(!1),m(""),z(""),_(null),B(null),mu([]),q("Usajili umefutwa kwenye kikao hiki. Unaweza kusajili upya.")},Nf=(y)=>{if(R){q("SIKU IMEISHA - HUWEZI KU-EDIT TENA! Mshahara umeshatangazwa na umefungwa.");return}if(!l){q("Sajili kwanza ili kuanza kazi.");return}if(!c){q("Fanya Sign In kwanza.");return}if(N[y])return;Ne(y),ou(!1)},Sf=()=>{if(M===null||!Kn)return;let y=Gr(new Date);x(($)=>({...$,[M]:y})),q(`Imethibitishwa: ${y} — Jukumu namba ${M} limekamilika.`),Wn(""),Hn(rn*60),Ne(null)},xf=()=>{if(!l){q("Sajili kwanza.");return}let y=new Date;m(Gr(y)),_(y),z(""),B(null),q("Sign In imerekodiwa. Karibu kazini!")},Ef=()=>{if(!C){q("Fanya Sign In kwanza.");return}let y=new Date;z(Gr(y)),B(y),q("Sign Out imerekodiwa. Asante kwa kazi njema!")},zf=()=>{if(!l)return;let y={date:Qn,completed:Z,earned:me,cut:Ut,signIn:c||"—",signOut:k||"—",pct:pe};mu(($)=>[y,...$]),p(!0),Ma(!1),Bn(!1),q(`Siku imefungwa — Ulipata TSh ${A(me)} • Ulimaliza ${Z}/48`),r("Ripoti")},Da=()=>{x({}),p(!1),m(""),z(""),_(null),B(null),fu(!0),Hn(rn*60),q("Siku mpya imeanza — Majukumu 48 mapya!")},Cf=[{name:"Dashboard",icon:It},{name:"Majukumu 48",icon:Un},{name:"Mshahara",icon:Ln},{name:"Ripoti",icon:Jr},{name:"Kanuni",icon:tn},{name:"Historia",icon:Qr}],_f=(y)=>{if(n===y){q(`Uko tayari kwenye ${y} — umerudishwa juu ya ukurasa.`),window.scrollTo({top:0,behavior:"smooth"});return}r(y),window.scrollTo({top:0,behavior:"smooth"})};return d("div",{className:"min-h-screen bg-[var(--bg)] text-[var(--ink)]",children:[d("div",{className:"sticky top-[var(--safe-area-inset-top)] z-40 bg-[#0F172A] text-white shadow-xl",children:[d("div",{className:"mx-auto max-w-[1440px] px-4 sm:px-6 lg:px-10 py-4 flex flex-wrap items-center justify-between gap-3",children:[d("div",{className:"flex items-center gap-3",children:[s("div",{className:"w-12 h-12 sm:w-14 sm:h-14 rounded-2xl bg-gradient-to-br from-[#0F766E] to-[#14B8A6] grid place-items-center text-2xl font-black shadow-lg",children:"W"}),d("div",{children:[d("h1",{className:"font-display font-black leading-none text-[19px] sm:text-[26px] lg:text-[32px] tracking-tight",children:["DR WILLIAM ",s("span",{className:"text-[#F59E0B]",children:"—"})," MTANZANIA CLINIC"]}),s("p",{className:"text-[11px] sm:text-[13px] text-teal-200 font-semibold tracking-wide mt-1",children:"MFUMO MAKINI WA KISASA WA MAJUKUMU YA OFISI | PRO"})]})]}),d("div",{className:"flex items-center gap-2 sm:gap-3",children:[d("div",{className:"hidden md:block bg-white/10 rounded-2xl px-4 py-2 text-right",children:[s("p",{className:"text-[12px] opacity-80 capitalize",children:Qn}),s("p",{className:"font-display font-bold text-lg leading-none mt-0.5 tabular-nums",children:Gr(e)})]}),d("div",{className:"bg-[#F59E0B] text-[#0F172A] rounded-full px-3 py-2 text-[12px] sm:text-sm font-extrabold flex items-center gap-1.5",children:[s("span",{className:"w-2 h-2 bg-emerald-600 rounded-full animate-pulse"})," LIVE • ",Gr(e)]})]})]}),l&&s("div",{className:"border-t border-white/10",children:d("div",{className:"mx-auto max-w-[1440px] px-4 sm:px-6 lg:px-10 py-3 flex flex-wrap items-center gap-3",children:[s("img",{src:l.photo,alt:l.name,className:"w-12 h-12 rounded-full object-cover border-[3px] border-[#F59E0B]"}),d("div",{className:"min-w-0",children:[s("p",{className:"font-bold truncate",children:l.name}),d("p",{className:"text-xs text-slate-300",children:[l.role," • ID: ",l.id]})]}),d("span",{className:"ml-auto bg-emerald-500/20 text-emerald-200 border border-emerald-400/30 rounded-full px-3 py-1.5 text-xs font-bold",children:["Mshahara: TSh ",A(l.salary)," / mwezi"]}),s("span",{className:"bg-white/10 rounded-full px-3 py-1.5 text-xs font-bold",children:"Kliniki: Dr William - Mtanzania"}),d("span",{className:"hidden sm:inline-flex bg-amber-400/20 text-amber-200 rounded-full px-3 py-1.5 text-xs font-bold",children:["● Leo: ",Z,"/48 • ",pe,"%"]})]})})]}),d("main",{className:"mx-auto max-w-[1440px] px-4 sm:px-6 lg:px-10 py-6 sm:py-10",children:[!l&&d("section",{className:"bg-white rounded-[24px] shadow-[0_20px_60px_rgba(15,23,42,.10)] overflow-hidden mb-8",children:[d("div",{className:"bg-gradient-to-r from-[#0F172A] via-[#0F766E] to-[#14B8A6] text-white p-6 sm:p-10 flex flex-wrap justify-between gap-4 items-end",children:[d("div",{children:[s("span",{className:"bg-[#F59E0B] text-[#0F172A] text-xs font-black px-3 py-1.5 rounded-full",children:"USAJILI • MARA MOJA TU"}),d("h2",{className:"font-display text-3xl sm:text-[44px] font-black leading-tight mt-4",children:["Usajili wa Mfanyakazi",s("br",{}),"— Mara Moja Tu"]}),s("p",{className:"text-teal-100 mt-2 max-w-xl",children:"Jaza taarifa zako sahihi. Baada ya kusajili, wasifu wako utaonekana juu kila wakati kwenye kikao hiki."})]}),d("div",{className:"text-right hidden md:block",children:[s("p",{className:"text-5xl font-black text-[#F59E0B]",children:"PRO"}),s("p",{className:"text-xs tracking-widest",children:"KUBWA • MAKINI • KISASA"})]})]}),d("form",{onSubmit:kf,className:"p-6 sm:p-10 grid lg:grid-cols-[300px_1fr] gap-8",children:[d("div",{className:"text-center",children:[s("div",{className:"w-[210px] h-[210px] mx-auto rounded-full overflow-hidden border-[6px] border-[#F59E0B] bg-[#F1F5F9] grid place-items-center shadow-xl",children:u?s("img",{src:u,alt:"Picha yako",className:"w-full h-full object-cover"}):d("div",{children:[s("p",{className:"text-6xl",children:"\uD83D\uDC64"}),s("p",{className:"text-sm text-slate-500 mt-2 font-semibold",children:"Picha yako hapa"})]})}),d("label",{className:"mt-5 inline-block bg-[#0F172A] text-white px-5 py-3 rounded-full font-bold cursor-pointer hover:bg-[#0F766E]",children:["\uD83D\uDCF8 Pakia Picha Yako",s("input",{type:"file",accept:"image/*",className:"hidden",onChange:yf})]}),s("p",{className:"text-xs text-slate-500 mt-2",children:"Picha itaonekana kwenye wasifu wako."})]}),d("div",{children:[d("div",{className:"grid sm:grid-cols-2 gap-5",children:[d("label",{className:"block",children:[s("span",{className:"font-bold text-sm",children:"Jina Kamili *"}),s("input",{value:i.name,onChange:(y)=>o({...i,name:y.target.value}),placeholder:"Mfano: Juma Peter Mushi",className:"mt-2 w-full border-2 border-slate-200 rounded-2xl px-4 py-4 text-base focus:border-[#14B8A6] outline-none"})]}),d("label",{className:"block",children:[s("span",{className:"font-bold text-sm",children:"Namba ya Mfanyakazi / ID *"}),s("input",{value:i.id,onChange:(y)=>o({...i,id:y.target.value}),placeholder:"Mfano: MTZ-001",className:"mt-2 w-full border-2 border-slate-200 rounded-2xl px-4 py-4 text-base focus:border-[#14B8A6] outline-none"})]}),d("label",{className:"block",children:[s("span",{className:"font-bold text-sm",children:"Cheo *"}),d("select",{value:i.role,onChange:(y)=>o({...i,role:y.target.value}),className:"mt-2 w-full border-2 border-slate-200 rounded-2xl px-4 py-4 bg-white",children:[s("option",{children:"Msaidizi wa Ofisi"}),s("option",{children:"Muuguzi Msaidizi"}),s("option",{children:"Mpokeaji"}),s("option",{children:"Mhudumu"})]})]}),d("label",{className:"block",children:[s("span",{className:"font-bold text-sm",children:"Mshahara wa Mwezi (TSh) *"}),s("input",{type:"number",min:"1",value:i.salary,onChange:(y)=>o({...i,salary:y.target.value}),placeholder:"Mfano: 200000",className:"mt-2 w-full border-2 border-slate-200 rounded-2xl px-4 py-4 text-base focus:border-[#14B8A6] outline-none"})]})]}),h&&s("p",{className:"mt-4 bg-red-50 text-red-700 px-4 py-3 rounded-xl font-bold",children:h}),s("button",{className:"mt-6 w-full sm:w-auto bg-gradient-to-r from-[#0F766E] to-[#14B8A6] text-white px-10 py-4 rounded-full font-black text-lg shadow-lg hover:scale-[1.02] active:scale-95",children:"Sajili & Anza Kazi →"}),d("p",{className:"mt-4 flex items-center gap-2 text-amber-700 bg-amber-50 border border-amber-200 px-4 py-3 rounded-xl text-sm font-semibold",children:[s(At,{size:16})," Umesajili mara moja - haiwezi kubadilishwa tena."]})]})]})]}),l&&d(Ot,{children:[d("div",{className:"bg-amber-50 border-2 border-amber-200 rounded-2xl px-5 py-3.5 flex flex-wrap gap-3 items-center justify-between mb-6",children:[d("p",{className:"font-bold text-amber-800 flex gap-2 items-center",children:[s(At,{size:18})," Umesajili mara moja - haiwezi kubadilishwa tena."]}),s("p",{className:"text-xs text-amber-700",children:"Kikao hiki ni cha ndani — hakuna kinachotumwa nje."})]}),vf&&d("div",{className:"bg-emerald-500 text-white rounded-[24px] px-6 py-5 flex gap-3 items-center font-bold text-lg mb-6 shadow-lg",children:[s(Rt,{})," Karibu Siku Mpya - ",Qn," - Majukumu 48 Mapya! ",s("button",{onClick:()=>fu(!1),className:"ml-auto bg-white/20 rounded-full px-3 py-1 text-sm",children:"Funga"})]}),R&&d("div",{className:"bg-slate-800 text-white rounded-[24px] px-6 py-5 font-bold text-lg mb-6 flex flex-wrap gap-3 items-center",children:[s(At,{})," Siku Imefungwa - Ulipata TSh ",A(me)," - Ulimaliza ",Z,"/48 ",s("button",{onClick:Da,className:"ml-auto bg-[#F59E0B] text-[#0F172A] px-5 py-2.5 rounded-full text-sm font-black",children:"Anza Siku Mpya"})]}),cu&&d("div",{className:"flash-red rounded-[24px] px-6 py-5 font-black text-lg mb-6 flex items-center gap-3 border-2 border-red-500",children:[s(Dn,{className:"shrink-0"})," ",cu," ",s("button",{onClick:()=>Wn(""),className:"ml-auto bg-white/80 rounded-full px-3 py-1 text-sm",children:"Nyamazisha"})]}),!c&&d("div",{className:"bg-red-50 border-2 border-red-200 text-red-800 rounded-[24px] px-6 py-4 font-bold mb-6 flex gap-2 items-center",children:[s(Vr,{})," Fanya Sign In kwanza — majukumu hayawezi kutiwa alama kabla ya Sign In."]})]}),s("nav",{className:"flex gap-2 sm:gap-3 overflow-x-auto no-scrollbar pb-2 -mx-1 px-1",children:Cf.map((y)=>{let $=y.icon,Se=n===y.name;return d("button",{onClick:()=>_f(y.name),className:`shrink-0 flex items-center gap-2 px-4 sm:px-6 py-3.5 sm:py-4 rounded-full font-black text-sm sm:text-base shadow-sm ${Se?"bg-[#0F172A] text-white shadow-xl scale-[1.02]":"bg-white text-slate-700 hover:bg-teal-50"}`,children:[s($,{size:19}),y.name,y.name==="Majukumu 48"&&d("span",{className:"bg-[#F59E0B] text-[#0F172A] text-xs px-2 py-0.5 rounded-full",children:[Z,"/48"]})]},y.name)})}),n==="Dashboard"&&s("div",{className:"mt-6 space-y-6",children:!l?d("div",{className:"bg-white rounded-[24px] p-8 sm:p-12 text-center shadow",children:[s("p",{className:"text-5xl mb-4",children:"\uD83D\uDC4B"}),s("h3",{className:"font-display text-2xl sm:text-3xl font-black",children:"Karibu Dr William - Mtanzania Clinic"}),s("p",{className:"text-slate-600 mt-3 max-w-2xl mx-auto",children:"Sajili hapo juu ili uone Dashibodi yako kamili, mshahara wa leo unaohesabiwa kiotomatiki na majukumu 48 ya siku."}),s("button",{onClick:()=>window.scrollTo({top:0,behavior:"smooth"}),className:"mt-6 bg-[#0F766E] text-white px-7 py-3.5 rounded-full font-bold",children:"Nenda Kwenye Usajili ↑"})]}):d(Ot,{children:[d("div",{className:"grid lg:grid-cols-[1.15fr_1fr] gap-6",children:[s("section",{className:"bg-white rounded-[24px] p-6 sm:p-9 shadow-[0_20px_50px_rgba(15,23,42,.08)]",children:d("div",{className:"flex flex-wrap gap-6 items-center",children:[d("div",{className:"relative shrink-0 mx-auto sm:mx-0",children:[d("svg",{width:"188",height:"188",viewBox:"0 0 188 188",children:[s("circle",{cx:"94",cy:"94",r:"78",fill:"none",stroke:"#E2E8F0",strokeWidth:"16"}),s("circle",{cx:"94",cy:"94",r:"78",fill:"none",stroke:vu,strokeWidth:"16",strokeLinecap:"round",strokeDasharray:gu,strokeDashoffset:gu*(1-pe/100),transform:"rotate(-90 94 94)"})]}),s("div",{className:"absolute inset-0 grid place-items-center text-center",children:d("div",{children:[d("p",{className:"font-display text-4xl font-black leading-none",children:[pe,"%"]}),s("p",{className:"text-xs font-bold text-slate-500 mt-1",children:"LEO"})]})})]}),d("div",{className:"flex-1 min-w-[260px]",children:[s("p",{className:"text-xs font-black tracking-widest text-[#0F766E]",children:"DASHIBODI PRO • MAENDELEO YA LEO"}),d("h3",{className:"font-display text-3xl font-black mt-2 leading-tight",children:["Umefikisha ",pe,"% Leo"]}),d("p",{className:"text-slate-600 mt-2",children:["Yaliyokamilika ",d("b",{className:"text-emerald-700",children:[Z,"/48"]})," • Yaliyobaki ",s("b",{className:"text-red-600",children:jr})," • Lengo ",s("b",{children:"100% YOTE YAKAMILIKE"})]}),s("div",{className:"mt-4 h-4 bg-slate-100 rounded-full overflow-hidden",children:s("div",{className:"h-full rounded-full transition-all",style:{width:`${pe}%`,background:vu}})}),s("div",{className:`mt-4 rounded-2xl px-4 py-3.5 font-bold ${pe===100?"bg-emerald-50 text-emerald-800":"bg-amber-50 text-amber-800"}`,children:pe===100?"\uD83C\uDF89 Hongera! Lengo limetimia 100%!":`⏳ Bado ${jr} - Maliza yote upate mshahara kamili!`}),d("div",{className:"mt-4 flex flex-wrap gap-2",children:[s("button",{onClick:()=>r("Majukumu 48"),className:"bg-[#0F172A] text-white px-6 py-3 rounded-full font-bold",children:"Endelea na Majukumu →"}),s("button",{onClick:()=>Ta(!0),className:"bg-white border-2 border-slate-200 px-6 py-3 rounded-full font-bold",children:"Tazama Ripoti"})]})]})]})}),d("section",{className:"bg-[#0F172A] text-white rounded-[24px] p-6 sm:p-9 shadow-xl relative overflow-hidden",children:[s("div",{className:"absolute -right-8 -top-8 w-40 h-40 bg-[#14B8A6]/30 rounded-full blur-2xl"}),d("div",{className:"flex justify-between items-start",children:[d("div",{children:[s("p",{className:"text-xs font-black tracking-widest text-teal-300",children:"MUDA WA KAZI"}),s("h3",{className:"font-display text-2xl font-black mt-2",children:"Leo ni Siku ya Kazi"})]}),s(Yr,{className:"text-[#F59E0B]"})]}),d("div",{className:"grid grid-cols-2 gap-3 mt-6",children:[d("div",{className:"bg-white/10 rounded-2xl p-4",children:[s("p",{className:"text-xs opacity-70",children:"Muda wa Kuingia"}),s("p",{className:"font-display text-2xl font-black mt-1",children:"07:30"}),d("p",{className:"text-xs mt-1 text-emerald-300",children:["Sign In: ",c||"—"]})]}),d("div",{className:"bg-white/10 rounded-2xl p-4",children:[s("p",{className:"text-xs opacity-70",children:"Kutoka"}),s("p",{className:"font-display text-2xl font-black mt-1",children:"17:00"}),d("p",{className:"text-xs mt-1 text-amber-300",children:["Sign Out: ",k||"—"]})]})]}),d("div",{className:"mt-4 bg-white/10 rounded-2xl p-4 flex flex-wrap justify-between gap-2",children:[s("span",{className:"font-bold",children:"Umekuwa Kazini:"}),d("b",{className:"text-[#F59E0B] text-lg",children:["Saa ",Ra," Dakika ",Oa]})]}),s("p",{className:"mt-3 text-sm text-slate-300",children:e<Yn?d(Ot,{children:["Countdown kuanza kazi: ",d("b",{className:"text-white",children:[Math.floor(Aa/3600),"h ",Math.floor(Aa%3600/60),"m ",Aa%60,"s"]})]}):e<Ia?d(Ot,{children:["Siku ya kazi inaendelea • Inabaki hadi 17:00: ",d("b",{className:"text-white",children:[Math.floor(Math.max(0,Ia.getTime()-e.getTime())/3600000),"h"]})]}):s(Ot,{children:"Muda wa kazi umeisha — hakikisha umefunga siku."})}),gf&&!c&&s("p",{className:"mt-3 bg-red-500 text-white px-4 py-2.5 rounded-xl font-bold text-sm",children:"⚠️ Umechelewa — Muda wa 07:30 umeshapita. Fanya Sign In sasa!"}),d("div",{className:"grid grid-cols-2 gap-3 mt-5",children:[d("button",{onClick:xf,disabled:!!c,className:"bg-emerald-500 hover:bg-emerald-400 disabled:opacity-50 disabled:cursor-not-allowed text-white py-4 rounded-2xl font-black text-base",children:["✓ SIGN IN",s("br",{}),s("span",{className:"text-xs font-bold opacity-90",children:"NIMEINGIA KAZINI"})]}),d("button",{onClick:Ef,disabled:!c||!!k,className:"bg-red-500 hover:bg-red-400 disabled:opacity-50 disabled:cursor-not-allowed text-white py-4 rounded-2xl font-black text-base",children:["✕ SIGN OUT",s("br",{}),s("span",{className:"text-xs font-bold opacity-90",children:"NIMETOKA KAZINI"})]})]}),s("p",{className:"text-xs text-slate-400 mt-3",children:"Muda kamili unarekodiwa kiotomatiki unapobonyeza."})]})]}),d("section",{className:"bg-white rounded-[24px] p-6 sm:p-9 shadow-[0_20px_50px_rgba(15,23,42,.08)]",children:[d("div",{className:"flex flex-wrap justify-between gap-3 items-start",children:[d("div",{children:[s("p",{className:"text-xs font-black tracking-widest text-[#0F766E]",children:"MSHAHARA • KIOTOMATIKI"}),s("h3",{className:"font-display text-2xl sm:text-3xl font-black mt-2",children:"Mshahara Wako wa Leo - Unahesabiwa Kiotomatiki"}),s("p",{className:"text-slate-600 mt-2",children:"Mshahara wa Siku = Mwezi ÷ 30 • Thamani Kila Jukumu = Siku ÷ 48 • Utalipwa = Yaliyokamilika × Thamani"})]}),d("button",{onClick:()=>Vn(`Mshahara wako wa mwezi ni shilingi ${A(el)}. Mshahara wa siku ni shilingi ${A(Dt)}. Kila jukumu lina thamani ya shilingi ${A(tl)}. Umekamilisha majukumu ${Z} kati ya 48. Utalipwa shilingi ${A(me)} leo.`),className:"bg-amber-400 text-[#0F172A] px-5 py-3 rounded-full font-black flex gap-2 items-center",children:[s(nn,{size:18})," Sikiliza Maelezo ya Mshahara"]})]}),d("div",{className:"grid sm:grid-cols-2 lg:grid-cols-4 gap-4 mt-7",children:[d("div",{className:"bg-[#F8FAFC] border border-slate-100 rounded-[20px] p-5",children:[s("p",{className:"text-sm font-bold text-slate-500",children:"Mshahara wa Siku"}),d("p",{className:"font-display text-2xl sm:text-[28px] font-black mt-2",children:["TSh ",A(Dt)]}),d("p",{className:"text-xs text-slate-500 mt-1",children:[A(el)," ÷ 30"]})]}),d("div",{className:"bg-teal-50 rounded-[20px] p-5",children:[s("p",{className:"text-sm font-bold text-teal-700",children:"Umekamilisha"}),d("p",{className:"font-display text-2xl sm:text-[28px] font-black mt-2",children:[Z," / 48"]}),d("p",{className:"text-xs text-teal-700 mt-1",children:["Kila jukumu = TSh ",A(tl)]})]}),d("div",{className:"bg-red-50 rounded-[20px] p-5",children:[s("p",{className:"text-sm font-bold text-red-600",children:"Kilichokatwa"}),d("p",{className:"font-display text-2xl sm:text-[28px] font-black mt-2 text-red-600",children:["TSh ",A(Ut)]}),s("p",{className:"text-xs text-red-600 mt-1",children:"Siku − Utalipwa"})]}),d("div",{className:"bg-emerald-600 text-white rounded-[20px] p-5 shadow-lg",children:[s("p",{className:"text-sm font-bold text-emerald-100",children:"Utalipwa Leo"}),d("p",{className:"font-display text-3xl font-black mt-2",children:["TSh ",A(me)]}),s("p",{className:"text-xs text-emerald-100 mt-1",children:"Maliza yote upate kamili"})]})]}),d("p",{className:"mt-5 bg-slate-900 text-white rounded-2xl px-5 py-4 font-semibold",children:["Mfano: 200,000 ÷ 30 = 6,667 • Jukumu 1 = 139 • ",Z===0?"Kamilisha jukumu la kwanza ili uanze kupata mshahara wa leo.":`Umeanza vizuri — endelea hadi 48 upate TSh ${A(Dt)} kamili.`]})]}),d("section",{className:"bg-white rounded-[24px] p-6 sm:p-9 shadow",children:[d("div",{className:"flex flex-wrap justify-between gap-3",children:[d("div",{children:[d("h3",{className:"font-display text-2xl font-black flex gap-2 items-center",children:[s(Dn,{className:"text-[#F59E0B]"})," Udhibiti wa Alarm"]}),s("p",{className:"text-slate-600 mt-1",children:"Alarm itakukumbusha kila baada ya muda uliochagua hadi utike jukumu linalofuata."})]}),s("span",{className:`px-4 py-2 rounded-full font-black text-sm h-fit ${Xr?"bg-emerald-100 text-emerald-700":"bg-slate-100 text-slate-600"}`,children:Xr?"● ALARM IMEWASHWA":"○ ALARM IMEZIMWA"})]}),d("div",{className:"flex flex-wrap gap-3 mt-6 items-center",children:[d("div",{className:"flex bg-slate-100 rounded-full p-1",children:[s("button",{onClick:()=>{su(10),Hn(600)},className:`px-5 py-2.5 rounded-full font-bold ${rn===10?"bg-[#0F172A] text-white":""}`,children:"10 Dakika"}),s("button",{onClick:()=>{su(15),Hn(900)},className:`px-5 py-2.5 rounded-full font-bold ${rn===15?"bg-[#0F172A] text-white":""}`,children:"15 Dakika"})]}),d("div",{className:"bg-[#0F172A] text-white rounded-full px-6 py-3 font-black tabular-nums text-lg",children:["⏳ ",String(Math.floor(du/60)).padStart(2,"0"),":",String(du%60).padStart(2,"0")]}),s("button",{onClick:()=>{Ma(!0),q("Alarm imewashwa.")},className:"bg-emerald-600 text-white px-6 py-3 rounded-full font-bold",children:"Washa Alarm"}),s("button",{onClick:()=>{Pa(3),Vn("Hii ni jaribio la alarm. Kazi inaendelea vizuri."),q("Jaribio la alarm limetumwa.")},className:"bg-amber-400 text-[#0F172A] px-6 py-3 rounded-full font-bold",children:"Jaribu Alarm"}),s("button",{onClick:()=>{Ma(!1),Wn(""),window.speechSynthesis.cancel()},className:"bg-white border-2 border-slate-200 px-6 py-3 rounded-full font-bold",children:"Nyamazisha"}),d("button",{onClick:()=>hf(!$n),className:"bg-slate-100 px-5 py-3 rounded-full font-bold flex gap-2 items-center",children:[$n?s(nn,{size:18}):s(Zr,{size:18})," Sauti ",$n?"ON":"OFF"]})]}),d("p",{className:"text-sm text-slate-500 mt-4",children:["Jukumu linalofuata: ",s("b",{className:"text-slate-800",children:We?`Namba ${We.num} — ${We.title}`:"Vyote vimekamilika \uD83C\uDF89"})]})]}),d("div",{className:"grid sm:grid-cols-3 gap-4",children:[d("button",{onClick:()=>r("Majukumu 48"),className:"bg-gradient-to-br from-[#0F766E] to-[#14B8A6] text-white rounded-[24px] p-6 text-left shadow-lg",children:[s(Un,{size:28}),s("p",{className:"font-black text-xl mt-3",children:"Majukumu 48"}),s("p",{className:"text-teal-100 text-sm mt-1",children:"Tika jukumu linalofuata sasa →"})]}),d("button",{onClick:()=>r("Mshahara"),className:"bg-[#0F172A] text-white rounded-[24px] p-6 text-left shadow-lg",children:[s(Ln,{size:28}),s("p",{className:"font-black text-xl mt-3",children:"Mshahara"}),d("p",{className:"text-slate-300 text-sm mt-1",children:["Utalipwa leo: TSh ",A(me)]})]}),d("button",{onClick:()=>Bn(!0),className:"bg-[#F59E0B] text-[#0F172A] rounded-[24px] p-6 text-left shadow-lg",children:[s(At,{size:28}),s("p",{className:"font-black text-xl mt-3",children:"Funga Siku ya Leo"}),s("p",{className:"text-amber-900 text-sm mt-1",children:"Baada ya kufunga huwezi ku-edit tena"})]})]})]})}),n==="Majukumu 48"&&d("div",{className:"mt-6",children:[d("div",{className:"bg-gradient-to-r from-[#0F172A] to-[#0F766E] text-white rounded-[24px] p-6 sm:p-8 flex flex-wrap gap-4 items-center justify-between",children:[d("div",{children:[s("h2",{className:"font-display text-3xl font-black",children:"Majukumu 48 ya Leo"}),s("p",{className:"text-teal-100 mt-1",children:"Tika kwa mpangilio. Jukumu linalofuata linaangaza dhahabu."})]}),d("div",{className:"bg-white/10 rounded-2xl px-5 py-3 text-center",children:[d("p",{className:"font-display text-2xl font-black",children:[Z,"/48"]}),d("p",{className:"text-xs",children:["• ",pe,"%"]})]})]}),R?s("div",{className:"mt-5 bg-slate-200 text-slate-700 rounded-2xl p-5 font-bold text-center",children:"\uD83D\uDD12 IMEFUNGWA — Siku imeisha. Anza siku mpya kwenye Dashibodi."}):!c?s("div",{className:"mt-5 bg-red-50 border-2 border-red-200 text-red-800 rounded-2xl p-5 font-bold text-center",children:"Fanya Sign In kwanza."}):null,s("div",{className:"space-y-8 mt-8",children:_a.map((y,$)=>{let Se=_a.slice(0,$).reduce((st,Oe)=>st+Oe.items.length,0);return d("section",{className:`rounded-[24px] p-5 sm:p-7 shadow ${y.gold?"bg-amber-50 border-2 border-amber-300":"bg-white"}`,children:[d("div",{className:"flex flex-wrap justify-between gap-2 items-center",children:[d("h3",{className:"font-display text-xl sm:text-2xl font-black",children:[y.section," ",y.gold&&s("span",{className:"text-[#F59E0B]",children:"★"})]}),d("span",{className:"bg-slate-900 text-white text-xs font-bold px-3 py-1.5 rounded-full",children:[y.items.filter((st,Oe)=>N[Se+Oe+1]).length,"/",y.items.length," yamekamilika"]})]}),y.note&&s("p",{className:"mt-2 bg-amber-100 text-amber-900 px-4 py-2.5 rounded-xl font-semibold text-sm",children:y.note}),s("div",{className:"grid md:grid-cols-2 gap-4 mt-5",children:y.items.map((st,Oe)=>{let he=Se+Oe+1,_e=!!N[he],yu=We?.num===he&&!R&&!!c;return d("div",{className:`rounded-[20px] p-5 flex gap-4 items-start border-2 ${yu?"pulse-gold bg-white":_e?"bg-emerald-50 border-emerald-200":"bg-[#F8FAFC] border-slate-100"}`,children:[s("button",{onClick:()=>Nf(he),disabled:_e||R,"aria-label":`Tiki jukumu ${he}`,className:`shrink-0 w-11 h-11 rounded-full grid place-items-center font-black text-lg border-2 ${_e?"bg-emerald-600 text-white border-emerald-600":"bg-white border-slate-300 hover:border-[#0F766E]"}`,children:_e?"✓":he}),d("div",{className:"flex-1 min-w-0",children:[d("div",{className:"flex flex-wrap gap-2 items-center",children:[d("span",{className:"text-xs font-black bg-slate-900 text-white px-2.5 py-1 rounded-full",children:["Namba ",he]}),s("span",{className:"text-[11px] font-bold bg-white border px-2 py-1 rounded-full",children:y.section.replace("SEHEMU ","Sehemu ")}),y.gold&&s("span",{className:"text-[11px] font-black bg-amber-400 px-2 py-1 rounded-full",children:"KUKUZA KLINIKI"})]}),s("p",{className:`font-bold text-[17px] leading-snug mt-2 ${_e?"line-through text-slate-500":""}`,children:st}),yu&&s("p",{className:"mt-2 inline-flex bg-[#F59E0B] text-[#0F172A] text-xs font-black px-3 py-1.5 rounded-full animate-pulse",children:"⭐ LINASUBIRI - TIKI SASA"}),_e&&d("p",{className:"mt-2 text-emerald-700 font-bold text-sm flex gap-1 items-center",children:[s(Pt,{size:16})," Imethibitishwa: ",N[he]]})]})]},he)})})]},y.section)})}),d("div",{className:"mt-8 bg-white rounded-[24px] p-6 flex flex-wrap gap-3 justify-between items-center shadow",children:[d("p",{className:"font-bold",children:["Umepiga hatua kubwa — ",Z,"/48 • Utalipwa TSh ",A(me)]}),s("button",{onClick:()=>Bn(!0),className:"bg-[#0F172A] text-white px-6 py-3 rounded-full font-bold",children:"Funga Siku ya Leo"})]})]}),n==="Mshahara"&&s("div",{className:"mt-6 space-y-6",children:d("section",{className:"bg-white rounded-[24px] p-6 sm:p-9 shadow",children:[s("h2",{className:"font-display text-3xl font-black",children:"Mshahara — Hesabu Kamili"}),s("p",{className:"text-slate-600 mt-2",children:"Kila jukumu linalokamilika linaongeza mshahara wako wa leo mara moja."}),l?d(Ot,{children:[d("div",{className:"grid sm:grid-cols-2 lg:grid-cols-4 gap-4 mt-7",children:[d("div",{className:"bg-[#F8FAFC] rounded-[20px] p-6",children:[s("p",{className:"font-bold text-slate-500 text-sm",children:"Mshahara wa Mwezi"}),d("p",{className:"font-display text-2xl font-black mt-2",children:["TSh ",A(el)]})]}),d("div",{className:"bg-teal-50 rounded-[20px] p-6",children:[s("p",{className:"font-bold text-teal-700 text-sm",children:"Mshahara wa Siku"}),d("p",{className:"font-display text-2xl font-black mt-2",children:["TSh ",A(Dt)]}),s("p",{className:"text-xs mt-1",children:"Mwezi ÷ 30"})]}),d("div",{className:"bg-amber-50 rounded-[20px] p-6",children:[s("p",{className:"font-bold text-amber-700 text-sm",children:"Thamani Kila Jukumu"}),d("p",{className:"font-display text-2xl font-black mt-2",children:["TSh ",A(tl)]}),s("p",{className:"text-xs mt-1",children:"Siku ÷ 48"})]}),d("div",{className:"bg-emerald-600 text-white rounded-[20px] p-6",children:[s("p",{className:"font-bold text-sm",children:"Utalipwa Leo"}),d("p",{className:"font-display text-3xl font-black mt-2",children:["TSh ",A(me)]})]})]}),d("div",{className:"mt-6 grid md:grid-cols-2 gap-4",children:[d("div",{className:"border-2 border-slate-100 rounded-[20px] p-6",children:[s("h4",{className:"font-black text-lg",children:"Mfano wa Hesabu"}),d("p",{className:"text-slate-600 mt-2 leading-relaxed",children:["Mfano: 200,000 ÷ 30 = 6,667 (siku moja).",s("br",{}),"6,667 ÷ 48 = 139 (jukumu moja).",s("br",{}),"Ukikamilisha majukumu 48 yote, unapata 6,667 kamili."]})]}),d("div",{className:"bg-slate-900 text-white rounded-[20px] p-6",children:[s("h4",{className:"font-black text-lg",children:"Hali Yako Leo"}),d("p",{className:"mt-2",children:["Umekamilisha ",d("b",{className:"text-emerald-300",children:[Z,"/48"]})," • Kilichokatwa: ",d("b",{className:"text-red-300",children:["TSh ",A(Ut)]}),s("br",{}),s("span",{className:"text-slate-300 text-sm",children:jr>0?`Maliza majukumu ${jr} yaliyobaki ili urejeshe TSh ${A(Ut)}.`:"Hongera! Hakuna kilichokatwa leo."})]}),d("button",{onClick:()=>Vn(`Utalipwa shilingi ${A(me)} leo. Kilichokatwa ni shilingi ${A(Ut)}.`),className:"mt-4 bg-amber-400 text-slate-900 px-5 py-2.5 rounded-full font-bold flex gap-2 items-center",children:[s(nn,{size:16})," Sikiliza Maelezo ya Mshahara"]})]})]})]}):s("p",{className:"mt-6 bg-amber-50 p-5 rounded-2xl font-bold",children:"Sajili kwanza ili kuona hesabu yako ya mshahara."})]})}),n==="Ripoti"&&s("div",{className:"mt-6",children:d("section",{className:"bg-white rounded-[24px] p-6 sm:p-9 shadow",children:[d("div",{className:"flex flex-wrap justify-between gap-3",children:[d("div",{children:[s("p",{className:"text-xs font-black tracking-widest text-[#0F766E]",children:"RIPOTI YA SIKU • IMEANDALIWA NA MFUMO"}),s("h2",{className:"font-display text-3xl font-black mt-2",children:"Ripoti ya Siku"})]}),s("button",{onClick:()=>Ta(!0),className:"bg-[#0F172A] text-white px-6 py-3 rounded-full font-bold",children:"Fungua Ripoti Kamili"})]}),l?d("div",{className:"grid md:grid-cols-3 gap-4 mt-7",children:[d("div",{className:"flex gap-4 items-center bg-[#F8FAFC] rounded-[20px] p-5",children:[s("img",{src:l.photo,alt:l.name,className:"w-20 h-20 rounded-full object-cover border-4 border-amber-400"}),d("div",{children:[s("p",{className:"font-black text-lg leading-tight",children:l.name}),d("p",{className:"text-sm text-slate-600",children:[l.role," • ID ",l.id]}),s("p",{className:"text-sm font-bold mt-1",children:Qn})]})]}),d("div",{className:"bg-teal-50 rounded-[20px] p-5",children:[s("p",{className:"text-sm font-bold text-teal-700",children:"Sign In / Out"}),d("p",{className:"font-black text-xl mt-2",children:[c||"—"," → ",k||"—"]}),d("p",{className:"text-sm mt-1",children:["Umekuwa kazini: Saa ",Ra," Dakika ",Oa]})]}),d("div",{className:"bg-emerald-600 text-white rounded-[20px] p-5",children:[s("p",{className:"text-sm font-bold",children:"Matokeo"}),d("p",{className:"font-black text-xl mt-2",children:[Z,"/48 • ",pe,"%"]}),d("p",{className:"text-sm mt-1",children:["Utalipwa: TSh ",A(me)," • Kilichokatwa: TSh ",A(Ut)]})]})]}):s("p",{className:"mt-6 font-bold bg-amber-50 p-5 rounded-2xl",children:"Sajili kwanza ili ripoti ijazwe na taarifa zako."}),d("div",{className:"mt-6 grid md:grid-cols-2 gap-4",children:[d("button",{onClick:Da,className:"bg-emerald-600 text-white p-5 rounded-[20px] font-black text-left",children:["Anza Siku Mpya (Reset Majukumu Pekee) →",s("span",{className:"block text-sm font-medium text-emerald-100 mt-1",children:"Majukumu pekee yataanza upya. Wasifu wako unabaki."})]}),d("button",{onClick:()=>Bn(!0),className:"bg-[#0F172A] text-white p-5 rounded-[20px] font-black text-left",children:["Funga Siku ya Leo →",s("span",{className:"block text-sm font-medium text-slate-300 mt-1",children:"Baada ya kufunga huwezi ku-edit tena."})]})]}),s("h3",{className:"font-black text-xl mt-8 mb-3",children:"Orodha ya Majukumu na Muda"}),s("div",{className:"divide-y divide-slate-100 border rounded-[20px] overflow-hidden",children:Ca.map((y)=>d("div",{className:"flex gap-3 px-4 py-3 items-center text-sm",children:[d("span",{className:"font-black w-8",children:[y.num,"."]}),s("span",{className:"flex-1",children:y.title}),s("span",{className:N[y.num]?"text-emerald-700 font-bold":"text-slate-400",children:N[y.num]?`✓ ${N[y.num]}`:"Bado"})]},y.num))})]})}),n==="Kanuni"&&s("div",{className:"mt-6",children:d("section",{className:"bg-white rounded-[24px] p-6 sm:p-9 shadow",children:[d("div",{className:"flex flex-wrap justify-between gap-3",children:[d("div",{children:[s("p",{className:"text-xs font-black tracking-widest text-[#0F766E]",children:"MIONGOZO NA KANUNI"}),s("h2",{className:"font-display text-3xl font-black mt-2",children:"Kanuni 15 za Kazi"}),s("p",{className:"text-slate-600 mt-2",children:"Soma zote kwa makini. Kazi bora inajengwa na nidhamu."})]}),s(tn,{size:48,className:"text-[#F59E0B]"})]}),s("div",{className:"grid md:grid-cols-2 gap-4 mt-7",children:ah.map((y,$)=>d("div",{className:"flex gap-4 bg-[#F8FAFC] rounded-[20px] p-5 border border-slate-100",children:[s("span",{className:"w-10 h-10 shrink-0 bg-[#0F172A] text-white rounded-full grid place-items-center font-black",children:$+1}),s("p",{className:"font-semibold leading-relaxed",children:y})]},$))}),d("label",{className:"mt-7 flex gap-3 items-start bg-emerald-50 border-2 border-emerald-200 rounded-[20px] p-5 cursor-pointer",children:[s("input",{type:"checkbox",checked:ff,onChange:(y)=>{if(pf(y.target.checked),y.target.checked)mf("Umehakiki kusoma kanuni - Asante"),q("Umehakiki kusoma kanuni - Asante")},className:"w-6 h-6 mt-0.5 accent-emerald-600"}),s("span",{className:"font-bold text-lg",children:"Nimesoma na Nimeelewa Kanuni Zote"})]}),uu&&d("p",{className:"mt-4 bg-emerald-600 text-white px-5 py-3.5 rounded-2xl font-bold flex gap-2",children:[s(ut,{})," ",uu]})]})}),n==="Historia"&&s("div",{className:"mt-6",children:d("section",{className:"bg-white rounded-[24px] p-6 sm:p-9 shadow",children:[s("h2",{className:"font-display text-3xl font-black",children:"Historia ya Siku"}),s("p",{className:"text-slate-600 mt-2",children:"Siku zilizofungwa kwenye kikao hiki zinaonekana hapa."}),pu.length===0?d("div",{className:"mt-7 bg-[#F8FAFC] rounded-[20px] p-8 text-center",children:[s("p",{className:"text-4xl mb-3",children:"\uD83D\uDCC5"}),s("p",{className:"font-bold text-lg",children:"Bado hakuna siku iliyofungwa."}),s("p",{className:"text-slate-500 mt-1",children:"Funga siku ya leo ili historia ianze kujazwa hapa."})]}):s("div",{className:"grid md:grid-cols-2 gap-4 mt-7",children:pu.map((y,$)=>d("div",{className:"border-2 border-slate-100 rounded-[20px] p-5",children:[s("p",{className:"font-black",children:y.date}),d("p",{className:"mt-3 text-2xl font-black",children:[y.completed,"/48 • ",y.pct,"%"]}),d("p",{className:"text-sm text-slate-600 mt-1",children:["Sign In ",y.signIn," • Sign Out ",y.signOut]}),d("p",{className:"mt-3",children:[d("span",{className:"text-emerald-700 font-bold",children:["Ulipata TSh ",A(y.earned)]})," • ",d("span",{className:"text-red-600 font-bold",children:["Kilichokatwa TSh ",A(y.cut)]})]})]},$))}),d("div",{className:"mt-8 bg-[#F8FAFC] rounded-[20px] p-6",children:[s("h3",{className:"font-black text-lg",children:"Hali ya Leo"}),s("p",{className:"mt-2 text-slate-700",children:l?`${l.name} • ${Z}/48 • ${pe}% • Utalipwa TSh ${A(me)} • ${R?"Siku imefungwa":"Siku bado wazi"}`:"Sajili kwanza."})]})]})}),l&&d("section",{className:"mt-8 bg-white rounded-[24px] p-6 shadow border border-slate-100",children:[s("h3",{className:"font-black",children:"Kuweka Upya Kikao (hiari)"}),d("p",{className:"text-sm text-slate-600 mt-1",children:["Andika ",s("b",{children:"FUTA"})," ili kufuta usajili na kuanza upya kwenye kikao hiki tu."]}),d("div",{className:"flex flex-wrap gap-3 mt-4",children:[s("input",{value:v,onChange:(y)=>S(y.target.value),placeholder:"Andika FUTA hapa",className:"border-2 border-slate-200 rounded-full px-5 py-3 font-bold uppercase flex-1 min-w-[200px]"}),s("button",{onClick:wf,className:"bg-red-50 text-red-700 border border-red-200 px-6 py-3 rounded-full font-bold",children:"Futa Usajili wa Kikao"})]})]}),d("footer",{className:"mt-10 text-center text-sm text-slate-500 pb-4",children:[s("p",{className:"font-black text-slate-700",children:"DR WILLIAM - MTANZANIA CLINIC • MFUMO MAKINI WA KISASA WA MAJUKUMU YA OFISI | PRO"}),s("p",{className:"mt-1",children:"Huduma bora • Nidhamu • Ufuatiliaji wa kila siku"})]})]}),M!==null&&s("div",{className:"fixed inset-0 z-50 bg-black/60 backdrop-blur-sm grid place-items-center p-4",role:"dialog","aria-modal":"true",children:d("div",{className:"bg-white w-full max-w-[640px] rounded-[28px] p-6 sm:p-9 shadow-2xl max-h-[92vh] overflow-y-auto",children:[d("div",{className:"flex justify-between items-start",children:[s("span",{className:"bg-red-100 text-red-700 px-3 py-1.5 rounded-full text-xs font-black",children:"UTHIBITISHO UNAHITAJIKA"}),s("button",{onClick:()=>Ne(null),className:"bg-slate-100 rounded-full p-2",children:s(bn,{})})]}),s("h3",{className:"font-display text-3xl font-black mt-4 leading-tight",children:"THIBITISHA UMETEKELEZA KWELI?"}),d("p",{className:"mt-3 text-lg",children:["Jukumu namba ",s("b",{children:M}),":"]}),s("p",{className:"mt-2 bg-[#F8FAFC] border-2 border-slate-100 rounded-2xl p-4 font-bold text-lg leading-relaxed",children:Ca.find((y)=>y.num===M)?.title}),d("div",{className:"mt-4 bg-red-50 border-2 border-red-200 rounded-2xl p-5",children:[d("p",{className:"font-black text-red-700 flex gap-2",children:[s(tn,{})," ONYO KALI:"]}),s("p",{className:"text-red-800 leading-relaxed mt-2 text-[15px]",children:"Ikibainika umejaza juu na hukutekeleza kweli, mshahara wako wa siku hiyo UTAKATWA KWA ASILIMIA 70% na utachukuliwa hatua kali za kinidhamu. Kwa mujibu wa kanuni za kazi na sheria za ajira Tanzania, udanganyifu na kujaza taarifa za uongo kazini ni kosa kubwa linaloweza kusababisha onyo kali la maandishi, kusimamishwa kazi bila malipo, au kufukuzwa kazi kabisa. Mkurugenzi anaweza kukagua wakati wowote."})]}),d("label",{className:"mt-5 flex gap-3 items-start bg-amber-50 border-2 border-amber-200 rounded-2xl p-4 cursor-pointer",children:[s("input",{type:"checkbox",checked:Kn,onChange:(y)=>ou(y.target.checked),className:"w-6 h-6 mt-0.5 accent-amber-500"}),s("span",{className:"font-bold",children:"Nathibitisha nimetekeleza kweli, siyo nimejaza juu tu"})]}),d("div",{className:"grid grid-cols-2 gap-3 mt-6",children:[s("button",{onClick:()=>Ne(null),className:"border-2 border-slate-200 py-4 rounded-full font-bold",children:"Ghairi"}),s("button",{onClick:Sf,disabled:!Kn,className:"bg-emerald-600 text-white py-4 rounded-full font-black disabled:opacity-40 disabled:cursor-not-allowed",children:"Nimethibitisha - Tiki Sasa ✓"})]})]})}),df&&s("div",{className:"fixed inset-0 z-50 bg-black/60 grid place-items-center p-4",role:"dialog","aria-modal":"true",children:d("div",{className:"bg-white w-full max-w-[560px] rounded-[28px] p-7 sm:p-9 shadow-2xl",children:[s("h3",{className:"font-display text-3xl font-black",children:"Funga Siku ya Leo?"}),s("p",{className:"mt-3 text-lg text-slate-600",children:"Una uhakika? Baada ya kufunga huwezi ku-edit tena."}),d("div",{className:"mt-5 bg-[#F8FAFC] rounded-2xl p-5 font-bold",children:["Siku Imefungwa - Ulipata TSh ",A(me)," - Ulimaliza ",Z,"/48"]}),d("div",{className:"grid grid-cols-2 gap-3 mt-6",children:[s("button",{onClick:()=>Bn(!1),className:"border-2 border-slate-200 py-4 rounded-full font-bold",children:"Ghairi"}),s("button",{onClick:zf,className:"bg-[#0F172A] text-white py-4 rounded-full font-black",children:"Ndiyo, Funga Siku"})]})]})}),cf&&s("div",{className:"fixed inset-0 z-50 bg-black/60 grid place-items-center p-4",role:"dialog","aria-modal":"true",children:d("div",{className:"bg-white w-full max-w-[760px] rounded-[28px] p-6 sm:p-9 shadow-2xl max-h-[92vh] overflow-y-auto",children:[d("div",{className:"flex justify-between",children:[d("div",{children:[s("p",{className:"text-xs font-black tracking-widest text-[#0F766E]",children:"RIPOTI YA SIKU • IMEANDALIWA NA MFUMO"}),s("h3",{className:"font-display text-3xl font-black mt-2",children:"Ripoti ya Siku"})]}),s("button",{onClick:()=>Ta(!1),className:"bg-slate-100 rounded-full p-2 h-fit",children:s(bn,{})})]}),l&&d("div",{className:"mt-6 flex gap-4 items-center",children:[s("img",{src:l.photo,alt:l.name,className:"w-20 h-20 rounded-full object-cover border-4 border-amber-400"}),d("div",{children:[s("p",{className:"font-black text-xl",children:l.name}),d("p",{className:"text-slate-600",children:["ID: ",l.id," • ",l.role]}),s("p",{className:"font-bold",children:Qn})]})]}),d("div",{className:"grid grid-cols-2 sm:grid-cols-4 gap-3 mt-6 text-center",children:[d("div",{className:"bg-slate-50 rounded-2xl p-4",children:[s("p",{className:"text-xs font-bold text-slate-500",children:"Sign In"}),s("p",{className:"font-black mt-1",children:c||"—"})]}),d("div",{className:"bg-slate-50 rounded-2xl p-4",children:[s("p",{className:"text-xs font-bold text-slate-500",children:"Sign Out"}),s("p",{className:"font-black mt-1",children:k||"—"})]}),d("div",{className:"bg-slate-50 rounded-2xl p-4",children:[s("p",{className:"text-xs font-bold text-slate-500",children:"Muda Kazini"}),d("p",{className:"font-black mt-1",children:[Ra,"h ",Oa,"m"]})]}),d("div",{className:"bg-emerald-50 rounded-2xl p-4",children:[s("p",{className:"text-xs font-bold text-emerald-700",children:"Matokeo"}),d("p",{className:"font-black mt-1",children:[Z,"/48 • ",pe,"%"]})]})]}),d("div",{className:"grid sm:grid-cols-3 gap-3 mt-3 text-center",children:[d("div",{className:"bg-teal-50 rounded-2xl p-4",children:[s("p",{className:"text-xs font-bold",children:"Utalipwa"}),d("p",{className:"font-black text-emerald-700",children:["TSh ",A(me)]})]}),d("div",{className:"bg-red-50 rounded-2xl p-4",children:[s("p",{className:"text-xs font-bold",children:"Kilichokatwa"}),d("p",{className:"font-black text-red-600",children:["TSh ",A(Ut)]})]}),d("div",{className:"bg-amber-50 rounded-2xl p-4",children:[s("p",{className:"text-xs font-bold",children:"Mshahara wa Siku"}),d("p",{className:"font-black",children:["TSh ",A(Dt)]})]})]}),s("h4",{className:"font-black text-lg mt-6 mb-2",children:"Majukumu Yote"}),s("div",{className:"divide-y divide-slate-100 border rounded-2xl overflow-hidden max-h-[260px] overflow-y-auto",children:Ca.map((y)=>d("div",{className:"flex gap-2 px-4 py-2.5 text-sm",children:[d("span",{className:"font-black w-8",children:[y.num,"."]}),s("span",{className:"flex-1",children:y.title}),s("span",{className:N[y.num]?"text-emerald-700 font-bold":"text-slate-400",children:N[y.num]?`✓ ${N[y.num]}`:"Bado"})]},y.num))}),d("div",{className:"grid grid-cols-2 gap-6 mt-10 pt-6 border-t",children:[d("div",{children:[s("p",{className:"font-bold",children:"Sahihi ya Mfanyakazi"}),s("p",{className:"mt-8 border-b-2 border-slate-300",children:"____________________"})]}),d("div",{children:[s("p",{className:"font-bold",children:"Sahihi ya Mkurugenzi"}),s("p",{className:"mt-8 border-b-2 border-slate-300",children:"____________________"})]})]}),s("button",{onClick:Da,className:"mt-8 w-full bg-emerald-600 text-white py-4 rounded-full font-black",children:"Anza Siku Mpya (Reset Majukumu Pekee)"})]})}),qr&&d("div",{className:"fixed bottom-5 left-1/2 -translate-x-1/2 z-[60] bg-[#0F172A] text-white px-6 py-4 rounded-full shadow-2xl font-bold text-center max-w-[92vw] flex gap-2 items-center",children:[s(ut,{className:"text-emerald-400 shrink-0"}),qr]})]})}sf.createRoot(document.getElementById("root")).render(s(uf.default.StrictMode,{children:s(iu,{})}));
</script>
  <script>(function(){function m(a){var h=a.getAttribute("href");if(!h)return;try{var u=new URL(h,document.baseURI);if(((u.protocol==="http:"||u.protocol==="https:")&&u.host!==location.host)||u.protocol==="mailto:"||u.protocol==="tel:"||u.protocol==="sms:"){a.target="_blank";a.rel="noopener noreferrer";}}catch(e){}}function s(){document.querySelectorAll("a[href]").forEach(m);}if(document.readyState!=="loading"){s();}else{document.addEventListener("DOMContentLoaded",s);}document.addEventListener("click",function(e){var a=e.target&&e.target.closest&&e.target.closest("a[href]");if(a){m(a);}},true);})();</script>
  <script type="application/json" data-clippy-inline-media-manifest="1">{"version":1,"slots":[]}</script>
</body>
</html>
