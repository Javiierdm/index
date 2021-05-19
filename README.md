/*!
* Based on Bootstrap v4.0.0 (https://getbootstrap.com) 
*/
@import url("https://fonts.googleapis.com/css?family=Montserrat:200,400,700");
/*!
 * Bootstrap v4.0.0 (https://getbootstrap.com)
 * Copyright 2011-2018 The Bootstrap Authors
 * Copyright 2011-2018 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
:root {
  --blue: #007bff;
  --indigo: #6610f2;
  --purple: #6f42c1;
  --pink: #e83e8c;
  --red: #dc3545;
  --orange: #fd7e14;
  --yellow: #ffc107;
  --green: #28a745;
  --teal: #20c997;
  --cyan: #17a2b8;
  --white: #fff;
  --gray: #6c757d;
  --gray-dark: #343a40;
  --primary: #f96332;
  --secondary: #888;
  --success: #18ce0f;
  --info: #2CA8FF;
  --warning: #FFB236;
  --danger: #FF3636;
  --light: #FFFFFF;
  --dark: #2c2c2c;
  --gray: #EEEEEE;
  --breakpoint-xs: 0;
  --breakpoint-sm: 576px;
  --breakpoint-md: 768px;
  --breakpoint-lg: 992px;
  --breakpoint-xl: 1200px;
  --font-family-sans-serif: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  --font-family-monospace: SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace; }

*,
*::before,
*::after {
  box-sizing: border-box; }

html {
  font-family: sans-serif;
  line-height: 1.15;
  -webkit-text-size-adjust: 100%;
  -ms-text-size-adjust: 100%;
  -ms-overflow-style: scrollbar;
  -webkit-tap-highlight-color: transparent; }

@-ms-viewport {
  width: device-width; }

article, aside, dialog, figcaption, figure, footer, header, hgroup, main, nav, section {
  display: block; }

body {
  margin: 0;
  font-family: Montserrat;
  font-size: 0.875rem;
  font-weight: 400;
  line-height: 1.6;
  color: #292b2c;
  text-align: left;
  background-color: white; }

[tabindex="-1"]:focus {
  outline: 0 !important; }

hr {
  box-sizing: content-box;
  height: 0;
  overflow: visible; }

h1, h2, h3, h4, h5, h6 {
  margin-top: 0;
  margin-bottom: 30px; }

p {
  margin-top: 0;
  margin-bottom: 1rem; }

abbr[title],
abbr[data-original-title] {
  text-decoration: underline;
  text-decoration: underline dotted;
  cursor: help;
  border-bottom: 0; }

address {
  margin-bottom: 1rem;
  font-style: normal;
  line-height: inherit; }

ol,
ul,
dl {
  margin-top: 0;
  margin-bottom: 1rem; }

ol ol,
ul ul,
ol ul,
ul ol {
  margin-bottom: 0; }

dt {
  font-weight: 700; }

dd {
  margin-bottom: .5rem;
  margin-left: 0; }

blockquote {
  margin: 0 0 1rem; }

dfn {
  font-style: italic; }

b,
strong {
  font-weight: bolder; }

small {
  font-size: 80%; }

sub,
sup {
  position: relative;
  font-size: 75%;
  line-height: 0;
  vertical-align: baseline; }

sub {
  bottom: -.25em; }

sup {
  top: -.5em; }

a {
  color: #f96332;
  text-decoration: none;
  background-color: transparent;
  -webkit-text-decoration-skip: objects; }
  a:hover {
    color: #d83a06;
    text-decoration: none; }

a:not([href]):not([tabindex]) {
  color: inherit;
  text-decoration: none; }
  a:not([href]):not([tabindex]):hover, a:not([href]):not([tabindex]):focus {
    color: inherit;
    text-decoration: none; }
  a:not([href]):not([tabindex]):focus {
    outline: 0; }

pre,
code,
kbd,
samp {
  font-family: monospace, monospace;
  font-size: 1em; }

pre {
  margin-top: 0;
  margin-bottom: 1rem;
  overflow: auto;
  -ms-overflow-style: scrollbar; }

figure {
  margin: 0 0 1rem; }

img {
  vertical-align: middle;
  border-style: none; }

svg:not(:root) {
  overflow: hidden; }

table {
  border-collapse: collapse; }

caption {
  padding-top: 0.75rem;
  padding-bottom: 0.75rem;
  color: #9A9A9A;
  text-align: left;
  caption-side: bottom; }

th {
  text-align: inherit; }

label {
  display: inline-block;
  margin-bottom: .5rem; }

button {
  border-radius: 0; }

button:focus {
  outline: 1px dotted;
  outline: 5px auto -webkit-focus-ring-color; }

input,
button,
select,
optgroup,
textarea {
  margin: 0;
  font-family: inherit;
  font-size: inherit;
  line-height: inherit; }

button,
input {
  overflow: visible; }

button,
select {
  text-transform: none; }

button,
html [type="button"],
[type="reset"],
[type="submit"] {
  -webkit-appearance: button; }

button::-moz-focus-inner,
[type="button"]::-moz-focus-inner,
[type="reset"]::-moz-focus-inner,
[type="submit"]::-moz-focus-inner {
  padding: 0;
  border-style: none; }

input[type="radio"],
input[type="checkbox"] {
  box-sizing: border-box;
  padding: 0; }

input[type="date"],
input[type="time"],
input[type="datetime-local"],
input[type="month"] {
  -webkit-appearance: listbox; }

textarea {
  overflow: auto;
  resize: vertical; }

fieldset {
  min-width: 0;
  padding: 0;
  margin: 0;
  border: 0; }

legend {
  display: block;
  width: 100%;
  max-width: 100%;
  padding: 0;
  margin-bottom: .5rem;
  font-size: 1.5rem;
  line-height: inherit;
  color: inherit;
  white-space: normal; }

progress {
  vertical-align: baseline; }

[type="number"]::-webkit-inner-spin-button,
[type="number"]::-webkit-outer-spin-button {
  height: auto; }

[type="search"] {
  outline-offset: -2px;
  -webkit-appearance: none; }

[type="search"]::-webkit-search-cancel-button,
[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none; }

::-webkit-file-upload-button {
  font: inherit;
  -webkit-appearance: button; }

output {
  display: inline-block; }

summary {
  display: list-item;
  cursor: pointer; }

template {
  display: none; }

[hidden] {
  display: none !important; }

h1, h2, h3, h4, h5, h6,
.h1, .h2, .h3, .h4, .h5, .h6 {
  margin-bottom: 30px;
  font-family: Montserrat;
  font-weight: 400;
  line-height: 1.4em;
  color: inherit; }

h1, .h1 {
  font-size: 3.5em; }

h2, .h2 {
  font-size: 2.5em; }

h3, .h3 {
  font-size: 2em; }

h4, .h4 {
  font-size: 1.714em; }

h5, .h5 {
  font-size: 1.57em; }

h6, .h6 {
  font-size: 1em; }

.lead {
  font-size: 1.3rem;
  font-weight: 300; }

.display-1 {
  font-size: 2.8em;
  font-weight: 300;
  line-height: 1.4em; }

.display-2 {
  font-size: 4.8125rem;
  font-weight: 300;
  line-height: 1.4em; }

.display-3 {
  font-size: 3.9375rem;
  font-weight: 300;
  line-height: 1.4em; }

.display-4 {
  font-size: 3.0625rem;
  font-weight: 300;
  line-height: 1.4em; }

hr {
  margin-top: 1rem;
  margin-bottom: 1rem;
  border: 0;
  border-top: 1px solid rgba(0, 0, 0, 0.1); }

small,
.small {
  font-size: 70%;
  font-weight: 400; }

mark,
.mark {
  padding: 0.2em;
  background-color: #fcf8e3; }

.list-unstyled {
  padding-left: 0;
  list-style: none; }

.list-inline {
  padding-left: 0;
  list-style: none; }

.list-inline-item {
  display: inline-block; }
  .list-inline-item:not(:last-child) {
    margin-right: 0.5rem; }

.initialism {
  font-size: 90%;
  text-transform: uppercase; }

.blockquote {
  margin-bottom: 1rem;
  font-size: 1.09375rem; }

.blockquote-footer {
  display: block;
  font-size: 80%;
  color: #6c757d; }
  .blockquote-footer::before {
    content: "\2014 \00A0"; }

.img-fluid {
  max-width: 100%;
  height: auto; }

.img-thumbnail {
  padding: 0.25rem;
  background-color: white;
  border: 1px solid #dee2e6;
  border-radius: 0.25rem;
  max-width: 100%;
  height: auto; }

.figure {
  display: inline-block; }

.figure-img {
  margin-bottom: 0.5rem;
  line-height: 1; }

.figure-caption {
  font-size: 90%;
  color: #6c757d; }

code,
kbd,
pre,
samp {
  font-family: SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace; }

code {
  font-size: 87.5%;
  color: #e83e8c;
  word-break: break-word; }
  a > code {
    color: inherit; }

kbd {
  padding: 0.2rem 0.4rem;
  font-size: 87.5%;
  color: #fff;
  background-color: #212529;
  border-radius: 0.2rem; }
  kbd kbd {
    padding: 0;
    font-size: 100%;
    font-weight: 700; }

pre {
  display: block;
  font-size: 87.5%;
  color: #212529; }
  pre code {
    font-size: inherit;
    color: inherit;
    word-break: normal; }

.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll; }

.container {
  width: 100%;
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto; }
  @media (min-width: 576px) {
    .container {
      max-width: 540px; } }
  @media (min-width: 768px) {
    .container {
      max-width: 720px; } }
  @media (min-width: 992px) {
    .container {
      max-width: 960px; } }
  @media (min-width: 1200px) {
    .container {
      max-width: 1140px; } }

.container-fluid {
  width: 100%;
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto; }

.row {
  display: flex;
  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px; }

.no-gutters {
  margin-right: 0;
  margin-left: 0; }
  .no-gutters > .col,
  .no-gutters > [class*="col-"] {
    padding-right: 0;
    padding-left: 0; }

.col-1, .col-2, .col-3, .col-4, .col-5, .col-6, .col-7, .col-8, .col-9, .col-10, .col-11, .col-12, .col,
.col-auto, .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12, .col-sm,
.col-sm-auto, .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12, .col-md,
.col-md-auto, .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12, .col-lg,
.col-lg-auto, .col-xl-1, .col-xl-2, .col-xl-3, .col-xl-4, .col-xl-5, .col-xl-6, .col-xl-7, .col-xl-8, .col-xl-9, .col-xl-10, .col-xl-11, .col-xl-12, .col-xl,
.col-xl-auto {
  position: relative;
  width: 100%;
  min-height: 1px;
  padding-right: 15px;
  padding-left: 15px; }

.col {
  flex-basis: 0;
  flex-grow: 1;
  max-width: 100%; }

.col-auto {
  flex: 0 0 auto;
  width: auto;
  max-width: none; }

.col-1 {
  flex: 0 0 8.33333%;
  max-width: 8.33333%; }

.col-2 {
  flex: 0 0 16.66667%;
  max-width: 16.66667%; }

.col-3 {
  flex: 0 0 25%;
  max-width: 25%; }

.col-4 {
  flex: 0 0 33.33333%;
  max-width: 33.33333%; }

.col-5 {
  flex: 0 0 41.66667%;
  max-width: 41.66667%; }

.col-6 {
  flex: 0 0 50%;
  max-width: 50%; }

.col-7 {
  flex: 0 0 58.33333%;
  max-width: 58.33333%; }

.col-8 {
  flex: 0 0 66.66667%;
  max-width: 66.66667%; }

.col-9 {
  flex: 0 0 75%;
  max-width: 75%; }

.col-10 {
  flex: 0 0 83.33333%;
  max-width: 83.33333%; }

.col-11 {
  flex: 0 0 91.66667%;
  max-width: 91.66667%; }

.col-12 {
  flex: 0 0 100%;
  max-width: 100%; }

.order-first {
  order: -1; }

.order-last {
  order: 13; }

.order-0 {
  order: 0; }

.order-1 {
  order: 1; }

.order-2 {
  order: 2; }

.order-3 {
  order: 3; }

.order-4 {
  order: 4; }

.order-5 {
  order: 5; }

.order-6 {
  order: 6; }

.order-7 {
  order: 7; }

.order-8 {
  order: 8; }

.order-9 {
  order: 9; }

.order-10 {
  order: 10; }

.order-11 {
  order: 11; }

.order-12 {
  order: 12; }

.offset-1 {
  margin-left: 8.33333%; }

.offset-2 {
  margin-left: 16.66667%; }

.offset-3 {
  margin-left: 25%; }

.offset-4 {
  margin-left: 33.33333%; }

.offset-5 {
  margin-left: 41.66667%; }

.offset-6 {
  margin-left: 50%; }

.offset-7 {
  margin-left: 58.33333%; }

.offset-8 {
  margin-left: 66.66667%; }

.offset-9 {
  margin-left: 75%; }

.offset-10 {
  margin-left: 83.33333%; }

.offset-11 {
  margin-left: 91.66667%; }

@media (min-width: 576px) {
  .col-sm {
    flex-basis: 0;
    flex-grow: 1;
    max-width: 100%; }
  .col-sm-auto {
    flex: 0 0 auto;
    width: auto;
    max-width: none; }
  .col-sm-1 {
    flex: 0 0 8.33333%;
    max-width: 8.33333%; }
  .col-sm-2 {
    flex: 0 0 16.66667%;
    max-width: 16.66667%; }
  .col-sm-3 {
    flex: 0 0 25%;
    max-width: 25%; }
  .col-sm-4 {
    flex: 0 0 33.33333%;
    max-width: 33.33333%; }
  .col-sm-5 {
    flex: 0 0 41.66667%;
    max-width: 41.66667%; }
  .col-sm-6 {
    flex: 0 0 50%;
    max-width: 50%; }
  .col-sm-7 {
    flex: 0 0 58.33333%;
    max-width: 58.33333%; }
  .col-sm-8 {
    flex: 0 0 66.66667%;
    max-width: 66.66667%; }
  .col-sm-9 {
    flex: 0 0 75%;
    max-width: 75%; }
  .col-sm-10 {
    flex: 0 0 83.33333%;
    max-width: 83.33333%; }
  .col-sm-11 {
    flex: 0 0 91.66667%;
    max-width: 91.66667%; }
  .col-sm-12 {
    flex: 0 0 100%;
    max-width: 100%; }
  .order-sm-first {
    order: -1; }
  .order-sm-last {
    order: 13; }
  .order-sm-0 {
    order: 0; }
  .order-sm-1 {
    order: 1; }
  .order-sm-2 {
    order: 2; }
  .order-sm-3 {
    order: 3; }
  .order-sm-4 {
    order: 4; }
  .order-sm-5 {
    order: 5; }
  .order-sm-6 {
    order: 6; }
  .order-sm-7 {
    order: 7; }
  .order-sm-8 {
    order: 8; }
  .order-sm-9 {
    order: 9; }
  .order-sm-10 {
    order: 10; }
  .order-sm-11 {
    order: 11; }
  .order-sm-12 {
    order: 12; }
  .offset-sm-0 {
    margin-left: 0; }
  .offset-sm-1 {
    margin-left: 8.33333%; }
  .offset-sm-2 {
    margin-left: 16.66667%; }
  .offset-sm-3 {
    margin-left: 25%; }
  .offset-sm-4 {
    margin-left: 33.33333%; }
  .offset-sm-5 {
    margin-left: 41.66667%; }
  .offset-sm-6 {
    margin-left: 50%; }
  .offset-sm-7 {
    margin-left: 58.33333%; }
  .offset-sm-8 {
    margin-left: 66.66667%; }
  .offset-sm-9 {
    margin-left: 75%; }
  .offset-sm-10 {
    margin-left: 83.33333%; }
  .offset-sm-11 {
    margin-left: 91.66667%; } }

@media (min-width: 768px) {
  .col-md {
    flex-basis: 0;
    flex-grow: 1;
    max-width: 100%; }
  .col-md-auto {
    flex: 0 0 auto;
    width: auto;
    max-width: none; }
  .col-md-1 {
    flex: 0 0 8.33333%;
    max-width: 8.33333%; }
  .col-md-2 {
    flex: 0 0 16.66667%;
    max-width: 16.66667%; }
  .col-md-3 {
    flex: 0 0 25%;
    max-width: 25%; }
  .col-md-4 {
    flex: 0 0 33.33333%;
    max-width: 33.33333%; }
  .col-md-5 {
    flex: 0 0 41.66667%;
    max-width: 41.66667%; }
  .col-md-6 {
    flex: 0 0 50%;
    max-width: 50%; }
  .col-md-7 {
    flex: 0 0 58.33333%;
    max-width: 58.33333%; }
  .col-md-8 {
    flex: 0 0 66.66667%;
    max-width: 66.66667%; }
  .col-md-9 {
    flex: 0 0 75%;
    max-width: 75%; }
  .col-md-10 {
    flex: 0 0 83.33333%;
    max-width: 83.33333%; }
  .col-md-11 {
    flex: 0 0 91.66667%;
    max-width: 91.66667%; }
  .col-md-12 {
    flex: 0 0 100%;
    max-width: 100%; }
  .order-md-first {
    order: -1; }
  .order-md-last {
    order: 13; }
  .order-md-0 {
    order: 0; }
  .order-md-1 {
    order: 1; }
  .order-md-2 {
    order: 2; }
  .order-md-3 {
    order: 3; }
  .order-md-4 {
    order: 4; }
  .order-md-5 {
    order: 5; }
  .order-md-6 {
    order: 6; }
  .order-md-7 {
    order: 7; }
  .order-md-8 {
    order: 8; }
  .order-md-9 {
    order: 9; }
  .order-md-10 {
    order: 10; }
  .order-md-11 {
    order: 11; }
  .order-md-12 {
    order: 12; }
  .offset-md-0 {
    margin-left: 0; }
  .offset-md-1 {
    margin-left: 8.33333%; }
  .offset-md-2 {
    margin-left: 16.66667%; }
  .offset-md-3 {
    margin-left: 25%; }
  .offset-md-4 {
    margin-left: 33.33333%; }
  .offset-md-5 {
    margin-left: 41.66667%; }
  .offset-md-6 {
    margin-left: 50%; }
  .offset-md-7 {
    margin-left: 58.33333%; }
  .offset-md-8 {
    margin-left: 66.66667%; }
  .offset-md-9 {
    margin-left: 75%; }
  .offset-md-10 {
    margin-left: 83.33333%; }
  .offset-md-11 {
    margin-left: 91.66667%; } }

@media (min-width: 992px) {
  .col-lg {
    flex-basis: 0;
    flex-grow: 1;
    max-width: 100%; }
  .col-lg-auto {
    flex: 0 0 auto;
    width: auto;
    max-width: none; }
  .col-lg-1 {
    flex: 0 0 8.33333%;
    max-width: 8.33333%; }
  .col-lg-2 {
    flex: 0 0 16.66667%;
    max-width: 16.66667%; }
  .col-lg-3 {
    flex: 0 0 25%;
    max-width: 25%; }
  .col-lg-4 {
    flex: 0 0 33.33333%;
    max-width: 33.33333%; }
  .col-lg-5 {
    flex: 0 0 41.66667%;
    max-width: 41.66667%; }
  .col-lg-6 {
    flex: 0 0 50%;
    max-width: 50%; }
  .col-lg-7 {
    flex: 0 0 58.33333%;
    max-width: 58.33333%; }
  .col-lg-8 {
    flex: 0 0 66.66667%;
    max-width: 66.66667%; }
  .col-lg-9 {
    flex: 0 0 75%;
    max-width: 75%; }
  .col-lg-10 {
    flex: 0 0 83.33333%;
    max-width: 83.33333%; }
  .col-lg-11 {
    flex: 0 0 91.66667%;
    max-width: 91.66667%; }
  .col-lg-12 {
    flex: 0 0 100%;
    max-width: 100%; }
  .order-lg-first {
    order: -1; }
  .order-lg-last {
    order: 13; }
  .order-lg-0 {
    order: 0; }
  .order-lg-1 {
    order: 1; }
  .order-lg-2 {
    order: 2; }
  .order-lg-3 {
    order: 3; }
  .order-lg-4 {
    order: 4; }
  .order-lg-5 {
    order: 5; }
  .order-lg-6 {
    order: 6; }
  .order-lg-7 {
    order: 7; }
  .order-lg-8 {
    order: 8; }
  .order-lg-9 {
    order: 9; }
  .order-lg-10 {
    order: 10; }
  .order-lg-11 {
    order: 11; }
  .order-lg-12 {
    order: 12; }
  .offset-lg-0 {
    margin-left: 0; }
  .offset-lg-1 {
    margin-left: 8.33333%; }
  .offset-lg-2 {
    margin-left: 16.66667%; }
  .offset-lg-3 {
    margin-left: 25%; }
  .offset-lg-4 {
    margin-left: 33.33333%; }
  .offset-lg-5 {
    margin-left: 41.66667%; }
  .offset-lg-6 {
    margin-left: 50%; }
  .offset-lg-7 {
    margin-left: 58.33333%; }
  .offset-lg-8 {
    margin-left: 66.66667%; }
  .offset-lg-9 {
    margin-left: 75%; }
  .offset-lg-10 {
    margin-left: 83.33333%; }
  .offset-lg-11 {
    margin-left: 91.66667%; } }

@media (min-width: 1200px) {
  .col-xl {
    flex-basis: 0;
    flex-grow: 1;
    max-width: 100%; }
  .col-xl-auto {
    flex: 0 0 auto;
    width: auto;
    max-width: none; }
  .col-xl-1 {
    flex: 0 0 8.33333%;
    max-width: 8.33333%; }
  .col-xl-2 {
    flex: 0 0 16.66667%;
    max-width: 16.66667%; }
  .col-xl-3 {
    flex: 0 0 25%;
    max-width: 25%; }
  .col-xl-4 {
    flex: 0 0 33.33333%;
    max-width: 33.33333%; }
  .col-xl-5 {
    flex: 0 0 41.66667%;
    max-width: 41.66667%; }
  .col-xl-6 {
    flex: 0 0 50%;
    max-width: 50%; }
  .col-xl-7 {
    flex: 0 0 58.33333%;
    max-width: 58.33333%; }
  .col-xl-8 {
    flex: 0 0 66.66667%;
    max-width: 66.66667%; }
  .col-xl-9 {
    flex: 0 0 75%;
    max-width: 75%; }
  .col-xl-10 {
    flex: 0 0 83.33333%;
    max-width: 83.33333%; }
  .col-xl-11 {
    flex: 0 0 91.66667%;
    max-width: 91.66667%; }
  .col-xl-12 {
    flex: 0 0 100%;
    max-width: 100%; }
  .order-xl-first {
    order: -1; }
  .order-xl-last {
    order: 13; }
  .order-xl-0 {
    order: 0; }
  .order-xl-1 {
    order: 1; }
  .order-xl-2 {
    order: 2; }
  .order-xl-3 {
    order: 3; }
  .order-xl-4 {
    order: 4; }
  .order-xl-5 {
    order: 5; }
  .order-xl-6 {
    order: 6; }
  .order-xl-7 {
    order: 7; }
  .order-xl-8 {
    order: 8; }
  .order-xl-9 {
    order: 9; }
  .order-xl-10 {
    order: 10; }
  .order-xl-11 {
    order: 11; }
  .order-xl-12 {
    order: 12; }
  .offset-xl-0 {
    margin-left: 0; }
  .offset-xl-1 {
    margin-left: 8.33333%; }
  .offset-xl-2 {
    margin-left: 16.66667%; }
  .offset-xl-3 {
    margin-left: 25%; }
  .offset-xl-4 {
    margin-left: 33.33333%; }
  .offset-xl-5 {
    margin-left: 41.66667%; }
  .offset-xl-6 {
    margin-left: 50%; }
  .offset-xl-7 {
    margin-left: 58.33333%; }
  .offset-xl-8 {
    margin-left: 66.66667%; }
  .offset-xl-9 {
    margin-left: 75%; }
  .offset-xl-10 {
    margin-left: 83.33333%; }
  .offset-xl-11 {
    margin-left: 91.66667%; } }

.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 1rem;
  background-color: transparent; }
  .table th,
  .table td {
    padding: 0.75rem;
    vertical-align: top;
    border-top: 1px solid #dee2e6; }
  .table thead th {
    vertical-align: bottom;
    border-bottom: 2px solid #dee2e6; }
  .table tbody + tbody {
    border-top: 2px solid #dee2e6; }
  .table .table {
    background-color: white; }

.table-sm th,
.table-sm td {
  padding: 0.3rem; }

.table-bordered {
  border: 1px solid #dee2e6; }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #dee2e6; }
  .table-bordered thead th,
  .table-bordered thead td {
    border-bottom-width: 2px; }

.table-striped tbody tr:nth-of-type(odd) {
  background-color: rgba(0, 0, 0, 0.05); }

.table-hover tbody tr:hover {
  background-color: rgba(0, 0, 0, 0.075); }

.table-primary,
.table-primary > th,
.table-primary > td {
  background-color: #fdd3c6; }

.table-hover .table-primary:hover {
  background-color: #fcc0ad; }
  .table-hover .table-primary:hover > td,
  .table-hover .table-primary:hover > th {
    background-color: #fcc0ad; }

.table-secondary,
.table-secondary > th,
.table-secondary > td {
  background-color: #dedede; }

.table-hover .table-secondary:hover {
  background-color: #d1d1d1; }
  .table-hover .table-secondary:hover > td,
  .table-hover .table-secondary:hover > th {
    background-color: #d1d1d1; }

.table-success,
.table-success > th,
.table-success > td {
  background-color: #bef1bc; }

.table-hover .table-success:hover {
  background-color: #aaeda7; }
  .table-hover .table-success:hover > td,
  .table-hover .table-success:hover > th {
    background-color: #aaeda7; }

.table-info,
.table-info > th,
.table-info > td {
  background-color: #c4e7ff; }

.table-hover .table-info:hover {
  background-color: #abddff; }
  .table-hover .table-info:hover > td,
  .table-hover .table-info:hover > th {
    background-color: #abddff; }

.table-warning,
.table-warning > th,
.table-warning > td {
  background-color: #ffe9c7; }

.table-hover .table-warning:hover {
  background-color: #ffdfae; }
  .table-hover .table-warning:hover > td,
  .table-hover .table-warning:hover > th {
    background-color: #ffdfae; }

.table-danger,
.table-danger > th,
.table-danger > td {
  background-color: #ffc7c7; }

.table-hover .table-danger:hover {
  background-color: #ffaeae; }
  .table-hover .table-danger:hover > td,
  .table-hover .table-danger:hover > th {
    background-color: #ffaeae; }

.table-light,
.table-light > th,
.table-light > td {
  background-color: white; }

.table-hover .table-light:hover {
  background-color: #f2f2f2; }
  .table-hover .table-light:hover > td,
  .table-hover .table-light:hover > th {
    background-color: #f2f2f2; }

.table-dark,
.table-dark > th,
.table-dark > td {
  background-color: #c4c4c4; }

.table-hover .table-dark:hover {
  background-color: #b7b7b7; }
  .table-hover .table-dark:hover > td,
  .table-hover .table-dark:hover > th {
    background-color: #b7b7b7; }

.table-gray,
.table-gray > th,
.table-gray > td {
  background-color: #fafafa; }

.table-hover .table-gray:hover {
  background-color: #ededed; }
  .table-hover .table-gray:hover > td,
  .table-hover .table-gray:hover > th {
    background-color: #ededed; }

.table-active,
.table-active > th,
.table-active > td {
  background-color: rgba(0, 0, 0, 0.075); }

.table-hover .table-active:hover {
  background-color: rgba(0, 0, 0, 0.075); }
  .table-hover .table-active:hover > td,
  .table-hover .table-active:hover > th {
    background-color: rgba(0, 0, 0, 0.075); }

.table .thead-dark th {
  color: white;
  background-color: #212529;
  border-color: #32383e; }

.table .thead-light th {
  color: #495057;
  background-color: #e9ecef;
  border-color: #dee2e6; }

.table-dark {
  color: white;
  background-color: #212529; }
  .table-dark th,
  .table-dark td,
  .table-dark thead th {
    border-color: #32383e; }
  .table-dark.table-bordered {
    border: 0; }
  .table-dark.table-striped tbody tr:nth-of-type(odd) {
    background-color: rgba(255, 255, 255, 0.05); }
  .table-dark.table-hover tbody tr:hover {
    background-color: rgba(255, 255, 255, 0.075); }

@media (max-width: 575.98px) {
  .table-responsive-sm {
    display: block;
    width: 100%;
    overflow-x: auto;
    -webkit-overflow-scrolling: touch;
    -ms-overflow-style: -ms-autohiding-scrollbar; }
    .table-responsive-sm > .table-bordered {
      border: 0; } }

@media (max-width: 767.98px) {
  .table-responsive-md {
    display: block;
    width: 100%;
    overflow-x: auto;
    -webkit-overflow-scrolling: touch;
    -ms-overflow-style: -ms-autohiding-scrollbar; }
    .table-responsive-md > .table-bordered {
      border: 0; } }

@media (max-width: 991.98px) {
  .table-responsive-lg {
    display: block;
    width: 100%;
    overflow-x: auto;
    -webkit-overflow-scrolling: touch;
    -ms-overflow-style: -ms-autohiding-scrollbar; }
    .table-responsive-lg > .table-bordered {
      border: 0; } }

@media (max-width: 1199.98px) {
  .table-responsive-xl {
    display: block;
    width: 100%;
    overflow-x: auto;
    -webkit-overflow-scrolling: touch;
    -ms-overflow-style: -ms-autohiding-scrollbar; }
    .table-responsive-xl > .table-bordered {
      border: 0; } }

.table-responsive {
  display: block;
  width: 100%;
  overflow-x: auto;
  -webkit-overflow-scrolling: touch;
  -ms-overflow-style: -ms-autohiding-scrollbar; }
  .table-responsive > .table-bordered {
    border: 0; }

.form-control {
  display: block;
  width: 100%;
  padding: 0.55rem 1.3rem;
  font-size: 0.875rem;
  line-height: 1.6;
  color: inherit;
  background-color: rgba(255, 255, 255, 0.1);
  background-clip: padding-box;
  border: 1px solid #ced4da;
  border-radius: 2.5rem;
  transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out; }
  .form-control::-ms-expand {
    background-color: transparent;
    border: 0; }
  .form-control:focus {
    color: inherit;
    background-color: rgba(255, 255, 255, 0.4);
    border-color: #fdc1ae;
    outline: 0;
    box-shadow: none; }
  .form-control::placeholder {
    color: rgba(41, 43, 44, 0.25);
    opacity: 1; }
  .form-control:disabled, .form-control[readonly] {
    background-color: #e9ecef;
    opacity: 1; }

select.form-control:not([size]):not([multiple]) {
  height: calc(2.29rem + 2px); }

select.form-control:focus::-ms-value {
  color: inherit;
  background-color: rgba(255, 255, 255, 0.1); }

.form-control-file,
.form-control-range {
  display: block;
  width: 100%; }

.col-form-label {
  padding-top: calc(0.55rem + 1px);
  padding-bottom: calc(0.55rem + 1px);
  margin-bottom: 0;
  font-size: inherit;
  line-height: 1.6; }

.col-form-label-lg {
  padding-top: calc(0.95rem + 1px);
  padding-bottom: calc(0.95rem + 1px);
  font-size: 1.09375rem;
  line-height: 1.5; }

.col-form-label-sm {
  padding-top: calc(0.25rem + 1px);
  padding-bottom: calc(0.25rem + 1px);
  font-size: 0.76562rem;
  line-height: 1.5; }

.form-control-plaintext {
  display: block;
  width: 100%;
  padding-top: 0.55rem;
  padding-bottom: 0.55rem;
  margin-bottom: 0;
  line-height: 1.6;
  background-color: transparent;
  border: solid transparent;
  border-width: 1px 0; }
  .form-control-plaintext.form-control-sm, .input-group-sm > .form-control-plaintext.form-control,
  .input-group-sm > .input-group-prepend > .form-control-plaintext.input-group-text,
  .input-group-sm > .input-group-append > .form-control-plaintext.input-group-text,
  .input-group-sm > .input-group-prepend > .form-control-plaintext.btn,
  .input-group-sm > .input-group-append > .form-control-plaintext.btn, .form-control-plaintext.form-control-lg, .input-group-lg > .form-control-plaintext.form-control,
  .input-group-lg > .input-group-prepend > .form-control-plaintext.input-group-text,
  .input-group-lg > .input-group-append > .form-control-plaintext.input-group-text,
  .input-group-lg > .input-group-prepend > .form-control-plaintext.btn,
  .input-group-lg > .input-group-append > .form-control-plaintext.btn {
    padding-right: 0;
    padding-left: 0; }

.form-control-sm, .input-group-sm > .form-control,
.input-group-sm > .input-group-prepend > .input-group-text,
.input-group-sm > .input-group-append > .input-group-text,
.input-group-sm > .input-group-prepend > .btn,
.input-group-sm > .input-group-append > .btn {
  padding: 0.25rem 0.8rem;
  font-size: 0.76562rem;
  line-height: 1.5;
  border-radius: 2.5rem; }

select.form-control-sm:not([size]):not([multiple]), .input-group-sm > select.form-control:not([size]):not([multiple]),
.input-group-sm > .input-group-prepend > select.input-group-text:not([size]):not([multiple]),
.input-group-sm > .input-group-append > select.input-group-text:not([size]):not([multiple]),
.input-group-sm > .input-group-prepend > select.btn:not([size]):not([multiple]),
.input-group-sm > .input-group-append > select.btn:not([size]):not([multiple]) {
  height: calc(1.64844rem + 2px); }

.form-control-lg, .input-group-lg > .form-control,
.input-group-lg > .input-group-prepend > .input-group-text,
.input-group-lg > .input-group-append > .input-group-text,
.input-group-lg > .input-group-prepend > .btn,
.input-group-lg > .input-group-append > .btn {
  padding: 0.95rem 3rem;
  font-size: 1.09375rem;
  line-height: 1.5;
  border-radius: 3rem; }

select.form-control-lg:not([size]):not([multiple]), .input-group-lg > select.form-control:not([size]):not([multiple]),
.input-group-lg > .input-group-prepend > select.input-group-text:not([size]):not([multiple]),
.input-group-lg > .input-group-append > select.input-group-text:not([size]):not([multiple]),
.input-group-lg > .input-group-prepend > select.btn:not([size]):not([multiple]),
.input-group-lg > .input-group-append > select.btn:not([size]):not([multiple]) {
  height: calc(3.54062rem + 2px); }

.form-group {
  margin-bottom: 1rem; }

.form-text {
  display: block;
  margin-top: 0.25rem; }

.form-row {
  display: flex;
  flex-wrap: wrap;
  margin-right: -5px;
  margin-left: -5px; }
  .form-row > .col,
  .form-row > [class*="col-"] {
    padding-right: 5px;
    padding-left: 5px; }

.form-check {
  position: relative;
  display: block;
  padding-left: 1.25rem; }

.form-check-input {
  position: absolute;
  margin-top: 0.3rem;
  margin-left: -1.25rem; }
  .form-check-input:disabled ~ .form-check-label {
    color: #9A9A9A; }

.form-check-label {
  margin-bottom: 0; }

.form-check-inline {
  display: inline-flex;
  align-items: center;
  padding-left: 0;
  margin-right: 0.75rem; }
  .form-check-inline .form-check-input {
    position: static;
    margin-top: 0;
    margin-right: 0.3125rem;
    margin-left: 0; }

.valid-feedback {
  display: none;
  width: 100%;
  margin-top: 0.25rem;
  font-size: 70%;
  color: #18ce0f; }

.valid-tooltip {
  position: absolute;
  top: 100%;
  z-index: 5;
  display: none;
  max-width: 100%;
  padding: .5rem;
  margin-top: .1rem;
  font-size: .875rem;
  line-height: 1;
  color: #fff;
  background-color: rgba(24, 206, 15, 0.8);
  border-radius: .2rem; }

.was-validated .form-control:valid, .form-control.is-valid, .was-validated
.custom-select:valid,
.custom-select.is-valid {
  border-color: #18ce0f; }
  .was-validated .form-control:valid:focus, .form-control.is-valid:focus, .was-validated
  .custom-select:valid:focus,
  .custom-select.is-valid:focus {
    border-color: #18ce0f;
    box-shadow: 0 0 0 0.2rem rgba(24, 206, 15, 0.25); }
  .was-validated .form-control:valid ~ .valid-feedback,
  .was-validated .form-control:valid ~ .valid-tooltip, .form-control.is-valid ~ .valid-feedback,
  .form-control.is-valid ~ .valid-tooltip, .was-validated
  .custom-select:valid ~ .valid-feedback,
  .was-validated
  .custom-select:valid ~ .valid-tooltip,
  .custom-select.is-valid ~ .valid-feedback,
  .custom-select.is-valid ~ .valid-tooltip {
    display: block; }

.was-validated .form-check-input:valid ~ .form-check-label, .form-check-input.is-valid ~ .form-check-label {
  color: #18ce0f; }

.was-validated .form-check-input:valid ~ .valid-feedback,
.was-validated .form-check-input:valid ~ .valid-tooltip, .form-check-input.is-valid ~ .valid-feedback,
.form-check-input.is-valid ~ .valid-tooltip {
  display: block; }

.was-validated .custom-control-input:valid ~ .custom-control-label, .custom-control-input.is-valid ~ .custom-control-label {
  color: #18ce0f; }
  .was-validated .custom-control-input:valid ~ .custom-control-label::before, .custom-control-input.is-valid ~ .custom-control-label::before {
    background-color: #6ff468; }

.was-validated .custom-control-input:valid ~ .valid-feedback,
.was-validated .custom-control-input:valid ~ .valid-tooltip, .custom-control-input.is-valid ~ .valid-feedback,
.custom-control-input.is-valid ~ .valid-tooltip {
  display: block; }

.was-validated .custom-control-input:valid:checked ~ .custom-control-label::before, .custom-control-input.is-valid:checked ~ .custom-control-label::before {
  background-color: #2bef21; }

.was-validated .custom-control-input:valid:focus ~ .custom-control-label::before, .custom-control-input.is-valid:focus ~ .custom-control-label::before {
  box-shadow: 0 0 0 1px white, 0 0 0 0.2rem rgba(24, 206, 15, 0.25); }

.was-validated .custom-file-input:valid ~ .custom-file-label, .custom-file-input.is-valid ~ .custom-file-label {
  border-color: #18ce0f; }
  .was-validated .custom-file-input:valid ~ .custom-file-label::before, .custom-file-input.is-valid ~ .custom-file-label::before {
    border-color: inherit; }

.was-validated .custom-file-input:valid ~ .valid-feedback,
.was-validated .custom-file-input:valid ~ .valid-tooltip, .custom-file-input.is-valid ~ .valid-feedback,
.custom-file-input.is-valid ~ .valid-tooltip {
  display: block; }

.was-validated .custom-file-input:valid:focus ~ .custom-file-label, .custom-file-input.is-valid:focus ~ .custom-file-label {
  box-shadow: 0 0 0 0.2rem rgba(24, 206, 15, 0.25); }

.invalid-feedback {
  display: none;
  width: 100%;
  margin-top: 0.25rem;
  font-size: 70%;
  color: #FF3636; }

.invalid-tooltip {
  position: absolute;
  top: 100%;
  z-index: 5;
  display: none;
  max-width: 100%;
  padding: .5rem;
  margin-top: .1rem;
  font-size: .875rem;
  line-height: 1;
  color: #fff;
  background-color: rgba(255, 54, 54, 0.8);
  border-radius: .2rem; }

.was-validated .form-control:invalid, .form-control.is-invalid, .was-validated
.custom-select:invalid,
.custom-select.is-invalid {
  border-color: #FF3636; }
  .was-validated .form-control:invalid:focus, .form-control.is-invalid:focus, .was-validated
  .custom-select:invalid:focus,
  .custom-select.is-invalid:focus {
    border-color: #FF3636;
    box-shadow: 0 0 0 0.2rem rgba(255, 54, 54, 0.25); }
  .was-validated .form-control:invalid ~ .invalid-feedback,
  .was-validated .form-control:invalid ~ .invalid-tooltip, .form-control.is-invalid ~ .invalid-feedback,
  .form-control.is-invalid ~ .invalid-tooltip, .was-validated
  .custom-select:invalid ~ .invalid-feedback,
  .was-validated
  .custom-select:invalid ~ .invalid-tooltip,
  .custom-select.is-invalid ~ .invalid-feedback,
  .custom-select.is-invalid ~ .invalid-tooltip {
    display: block; }

.was-validated .form-check-input:invalid ~ .form-check-label, .form-check-input.is-invalid ~ .form-check-label {
  color: #FF3636; }

.was-validated .form-check-input:invalid ~ .invalid-feedback,
.was-validated .form-check-input:invalid ~ .invalid-tooltip, .form-check-input.is-invalid ~ .invalid-feedback,
.form-check-input.is-invalid ~ .invalid-tooltip {
  display: block; }

.was-validated .custom-control-input:invalid ~ .custom-control-label, .custom-control-input.is-invalid ~ .custom-control-label {
  color: #FF3636; }
  .was-validated .custom-control-input:invalid ~ .custom-control-label::before, .custom-control-input.is-invalid ~ .custom-control-label::before {
    background-color: #ffb6b6; }

.was-validated .custom-control-input:invalid ~ .invalid-feedback,
.was-validated .custom-control-input:invalid ~ .invalid-tooltip, .custom-control-input.is-invalid ~ .invalid-feedback,
.custom-control-input.is-invalid ~ .invalid-tooltip {
  display: block; }

.was-validated .custom-control-input:invalid:checked ~ .custom-control-label::before, .custom-control-input.is-invalid:checked ~ .custom-control-label::before {
  background-color: #ff6969; }

.was-validated .custom-control-input:invalid:focus ~ .custom-control-label::before, .custom-control-input.is-invalid:focus ~ .custom-control-label::before {
  box-shadow: 0 0 0 1px white, 0 0 0 0.2rem rgba(255, 54, 54, 0.25); }

.was-validated .custom-file-input:invalid ~ .custom-file-label, .custom-file-input.is-invalid ~ .custom-file-label {
  border-color: #FF3636; }
  .was-validated .custom-file-input:invalid ~ .custom-file-label::before, .custom-file-input.is-invalid ~ .custom-file-label::before {
    border-color: inherit; }

.was-validated .custom-file-input:invalid ~ .invalid-feedback,
.was-validated .custom-file-input:invalid ~ .invalid-tooltip, .custom-file-input.is-invalid ~ .invalid-feedback,
.custom-file-input.is-invalid ~ .invalid-tooltip {
  display: block; }

.was-validated .custom-file-input:invalid:focus ~ .custom-file-label, .custom-file-input.is-invalid:focus ~ .custom-file-label {
  box-shadow: 0 0 0 0.2rem rgba(255, 54, 54, 0.25); }

.form-inline {
  display: flex;
  flex-flow: row wrap;
  align-items: center; }
  .form-inline .form-check {
    width: 100%; }
  @media (min-width: 576px) {
    .form-inline label {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 0; }
    .form-inline .form-group {
      display: flex;
      flex: 0 0 auto;
      flex-flow: row wrap;
      align-items: center;
      margin-bottom: 0; }
    .form-inline .form-control {
      display: inline-block;
      width: auto;
      vertical-align: middle; }
    .form-inline .form-control-plaintext {
      display: inline-block; }
    .form-inline .input-group {
      width: auto; }
    .form-inline .form-check {
      display: flex;
      align-items: center;
      justify-content: center;
      width: auto;
      padding-left: 0; }
    .form-inline .form-check-input {
      position: relative;
      margin-top: 0;
      margin-right: 0.25rem;
      margin-left: 0; }
    .form-inline .custom-control {
      align-items: center;
      justify-content: center; }
    .form-inline .custom-control-label {
      margin-bottom: 0; } }

.btn {
  display: inline-block;
  font-weight: 400;
  text-align: center;
  white-space: nowrap;
  vertical-align: middle;
  user-select: none;
  border: 1px solid transparent;
  padding: 0.55rem 1.3rem;
  font-size: 0.875rem;
  line-height: 1.2rem;
  border-radius: 0.25rem;
  transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out; }
  .btn:hover, .btn:focus {
    text-decoration: none; }
  .btn:focus, .btn.focus {
    outline: 0;
    box-shadow: none; }
  .btn.disabled, .btn:disabled {
    opacity: 0.65; }
  .btn:not(:disabled):not(.disabled) {
    cursor: pointer; }
  .btn:not(:disabled):not(.disabled):active, .btn:not(:disabled):not(.disabled).active {
    background-image: none; }

a.btn.disabled,
fieldset:disabled a.btn {
  pointer-events: none; }

.btn-primary {
  color: #fff;
  background-color: #f96332;
  border-color: #f96332; }
  .btn-primary:hover {
    color: #fff;
    background-color: #f8470d;
    border-color: #f14107; }
  .btn-primary:focus, .btn-primary.focus {
    box-shadow: 0 0 0 0.2rem rgba(249, 99, 50, 0.5); }
  .btn-primary.disabled, .btn-primary:disabled {
    color: #fff;
    background-color: #f96332;
    border-color: #f96332; }
  .btn-primary:not(:disabled):not(.disabled):active, .btn-primary:not(:disabled):not(.disabled).active,
  .show > .btn-primary.dropdown-toggle {
    color: #fff;
    background-color: #f14107;
    border-color: #e53d07; }
    .btn-primary:not(:disabled):not(.disabled):active:focus, .btn-primary:not(:disabled):not(.disabled).active:focus,
    .show > .btn-primary.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(249, 99, 50, 0.5); }

.btn-secondary {
  color: #fff;
  background-color: #888;
  border-color: #888; }
  .btn-secondary:hover {
    color: #fff;
    background-color: #757575;
    border-color: #6f6f6f; }
  .btn-secondary:focus, .btn-secondary.focus {
    box-shadow: 0 0 0 0.2rem rgba(136, 136, 136, 0.5); }
  .btn-secondary.disabled, .btn-secondary:disabled {
    color: #fff;
    background-color: #888;
    border-color: #888; }
  .btn-secondary:not(:disabled):not(.disabled):active, .btn-secondary:not(:disabled):not(.disabled).active,
  .show > .btn-secondary.dropdown-toggle {
    color: #fff;
    background-color: #6f6f6f;
    border-color: #686868; }
    .btn-secondary:not(:disabled):not(.disabled):active:focus, .btn-secondary:not(:disabled):not(.disabled).active:focus,
    .show > .btn-secondary.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(136, 136, 136, 0.5); }

.btn-success {
  color: #fff;
  background-color: #18ce0f;
  border-color: #18ce0f; }
  .btn-success:hover {
    color: #fff;
    background-color: #14aa0c;
    border-color: #129e0c; }
  .btn-success:focus, .btn-success.focus {
    box-shadow: 0 0 0 0.2rem rgba(24, 206, 15, 0.5); }
  .btn-success.disabled, .btn-success:disabled {
    color: #fff;
    background-color: #18ce0f;
    border-color: #18ce0f; }
  .btn-success:not(:disabled):not(.disabled):active, .btn-success:not(:disabled):not(.disabled).active,
  .show > .btn-success.dropdown-toggle {
    color: #fff;
    background-color: #129e0c;
    border-color: #11930b; }
    .btn-success:not(:disabled):not(.disabled):active:focus, .btn-success:not(:disabled):not(.disabled).active:focus,
    .show > .btn-success.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(24, 206, 15, 0.5); }

.btn-info {
  color: #fff;
  background-color: #2CA8FF;
  border-color: #2CA8FF; }
  .btn-info:hover {
    color: #fff;
    background-color: #0698ff;
    border-color: #0092f8; }
  .btn-info:focus, .btn-info.focus {
    box-shadow: 0 0 0 0.2rem rgba(44, 168, 255, 0.5); }
  .btn-info.disabled, .btn-info:disabled {
    color: #fff;
    background-color: #2CA8FF;
    border-color: #2CA8FF; }
  .btn-info:not(:disabled):not(.disabled):active, .btn-info:not(:disabled):not(.disabled).active,
  .show > .btn-info.dropdown-toggle {
    color: #fff;
    background-color: #0092f8;
    border-color: #008aeb; }
    .btn-info:not(:disabled):not(.disabled):active:focus, .btn-info:not(:disabled):not(.disabled).active:focus,
    .show > .btn-info.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(44, 168, 255, 0.5); }

.btn-warning {
  color: #fff;
  background-color: #FFB236;
  border-color: #FFB236; }
  .btn-warning:hover {
    color: #fff;
    background-color: #ffa310;
    border-color: #ff9e03; }
  .btn-warning:focus, .btn-warning.focus {
    box-shadow: 0 0 0 0.2rem rgba(255, 178, 54, 0.5); }
  .btn-warning.disabled, .btn-warning:disabled {
    color: #fff;
    background-color: #FFB236;
    border-color: #FFB236; }
  .btn-warning:not(:disabled):not(.disabled):active, .btn-warning:not(:disabled):not(.disabled).active,
  .show > .btn-warning.dropdown-toggle {
    color: #fff;
    background-color: #ff9e03;
    border-color: #f59700; }
    .btn-warning:not(:disabled):not(.disabled):active:focus, .btn-warning:not(:disabled):not(.disabled).active:focus,
    .show > .btn-warning.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(255, 178, 54, 0.5); }

.btn-danger {
  color: #fff;
  background-color: #FF3636;
  border-color: #FF3636; }
  .btn-danger:hover {
    color: #fff;
    background-color: #ff1010;
    border-color: #ff0303; }
  .btn-danger:focus, .btn-danger.focus {
    box-shadow: 0 0 0 0.2rem rgba(255, 54, 54, 0.5); }
  .btn-danger.disabled, .btn-danger:disabled {
    color: #fff;
    background-color: #FF3636;
    border-color: #FF3636; }
  .btn-danger:not(:disabled):not(.disabled):active, .btn-danger:not(:disabled):not(.disabled).active,
  .show > .btn-danger.dropdown-toggle {
    color: #fff;
    background-color: #ff0303;
    border-color: #f50000; }
    .btn-danger:not(:disabled):not(.disabled):active:focus, .btn-danger:not(:disabled):not(.disabled).active:focus,
    .show > .btn-danger.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(255, 54, 54, 0.5); }

.btn-light {
  color: #888;
  background-color: #FFFFFF;
  border-color: #FFFFFF; }
  .btn-light:hover {
    color: #888;
    background-color: #ececec;
    border-color: #e6e6e6; }
  .btn-light:focus, .btn-light.focus {
    box-shadow: 0 0 0 0.2rem rgba(255, 255, 255, 0.5); }
  .btn-light.disabled, .btn-light:disabled {
    color: #888;
    background-color: #FFFFFF;
    border-color: #FFFFFF; }
  .btn-light:not(:disabled):not(.disabled):active, .btn-light:not(:disabled):not(.disabled).active,
  .show > .btn-light.dropdown-toggle {
    color: #888;
    background-color: #e6e6e6;
    border-color: #dfdfdf; }
    .btn-light:not(:disabled):not(.disabled):active:focus, .btn-light:not(:disabled):not(.disabled).active:focus,
    .show > .btn-light.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(255, 255, 255, 0.5); }

.btn-dark {
  color: #fff;
  background-color: #2c2c2c;
  border-color: #2c2c2c; }
  .btn-dark:hover {
    color: #fff;
    background-color: #191919;
    border-color: #131313; }
  .btn-dark:focus, .btn-dark.focus {
    box-shadow: 0 0 0 0.2rem rgba(44, 44, 44, 0.5); }
  .btn-dark.disabled, .btn-dark:disabled {
    color: #fff;
    background-color: #2c2c2c;
    border-color: #2c2c2c; }
  .btn-dark:not(:disabled):not(.disabled):active, .btn-dark:not(:disabled):not(.disabled).active,
  .show > .btn-dark.dropdown-toggle {
    color: #fff;
    background-color: #131313;
    border-color: #0c0c0c; }
    .btn-dark:not(:disabled):not(.disabled):active:focus, .btn-dark:not(:disabled):not(.disabled).active:focus,
    .show > .btn-dark.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(44, 44, 44, 0.5); }

.btn-gray {
  color: #888;
  background-color: #EEEEEE;
  border-color: #EEEEEE; }
  .btn-gray:hover {
    color: #888;
    background-color: #dbdbdb;
    border-color: #d5d5d5; }
  .btn-gray:focus, .btn-gray.focus {
    box-shadow: 0 0 0 0.2rem rgba(238, 238, 238, 0.5); }
  .btn-gray.disabled, .btn-gray:disabled {
    color: #888;
    background-color: #EEEEEE;
    border-color: #EEEEEE; }
  .btn-gray:not(:disabled):not(.disabled):active, .btn-gray:not(:disabled):not(.disabled).active,
  .show > .btn-gray.dropdown-toggle {
    color: #888;
    background-color: #d5d5d5;
    border-color: #cecece; }
    .btn-gray:not(:disabled):not(.disabled):active:focus, .btn-gray:not(:disabled):not(.disabled).active:focus,
    .show > .btn-gray.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(238, 238, 238, 0.5); }

.btn-outline-primary {
  color: #f96332;
  background-color: transparent;
  background-image: none;
  border-color: #f96332; }
  .btn-outline-primary:hover {
    color: #fff;
    background-color: #f96332;
    border-color: #f96332; }
  .btn-outline-primary:focus, .btn-outline-primary.focus {
    box-shadow: 0 0 0 0.2rem rgba(249, 99, 50, 0.5); }
  .btn-outline-primary.disabled, .btn-outline-primary:disabled {
    color: #f96332;
    background-color: transparent; }
  .btn-outline-primary:not(:disabled):not(.disabled):active, .btn-outline-primary:not(:disabled):not(.disabled).active,
  .show > .btn-outline-primary.dropdown-toggle {
    color: #fff;
    background-color: #f96332;
    border-color: #f96332; }
    .btn-outline-primary:not(:disabled):not(.disabled):active:focus, .btn-outline-primary:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-primary.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(249, 99, 50, 0.5); }

.btn-outline-secondary {
  color: #888;
  background-color: transparent;
  background-image: none;
  border-color: #888; }
  .btn-outline-secondary:hover {
    color: #fff;
    background-color: #888;
    border-color: #888; }
  .btn-outline-secondary:focus, .btn-outline-secondary.focus {
    box-shadow: 0 0 0 0.2rem rgba(136, 136, 136, 0.5); }
  .btn-outline-secondary.disabled, .btn-outline-secondary:disabled {
    color: #888;
    background-color: transparent; }
  .btn-outline-secondary:not(:disabled):not(.disabled):active, .btn-outline-secondary:not(:disabled):not(.disabled).active,
  .show > .btn-outline-secondary.dropdown-toggle {
    color: #fff;
    background-color: #888;
    border-color: #888; }
    .btn-outline-secondary:not(:disabled):not(.disabled):active:focus, .btn-outline-secondary:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-secondary.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(136, 136, 136, 0.5); }

.btn-outline-success {
  color: #18ce0f;
  background-color: transparent;
  background-image: none;
  border-color: #18ce0f; }
  .btn-outline-success:hover {
    color: #fff;
    background-color: #18ce0f;
    border-color: #18ce0f; }
  .btn-outline-success:focus, .btn-outline-success.focus {
    box-shadow: 0 0 0 0.2rem rgba(24, 206, 15, 0.5); }
  .btn-outline-success.disabled, .btn-outline-success:disabled {
    color: #18ce0f;
    background-color: transparent; }
  .btn-outline-success:not(:disabled):not(.disabled):active, .btn-outline-success:not(:disabled):not(.disabled).active,
  .show > .btn-outline-success.dropdown-toggle {
    color: #fff;
    background-color: #18ce0f;
    border-color: #18ce0f; }
    .btn-outline-success:not(:disabled):not(.disabled):active:focus, .btn-outline-success:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-success.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(24, 206, 15, 0.5); }

.btn-outline-info {
  color: #2CA8FF;
  background-color: transparent;
  background-image: none;
  border-color: #2CA8FF; }
  .btn-outline-info:hover {
    color: #fff;
    background-color: #2CA8FF;
    border-color: #2CA8FF; }
  .btn-outline-info:focus, .btn-outline-info.focus {
    box-shadow: 0 0 0 0.2rem rgba(44, 168, 255, 0.5); }
  .btn-outline-info.disabled, .btn-outline-info:disabled {
    color: #2CA8FF;
    background-color: transparent; }
  .btn-outline-info:not(:disabled):not(.disabled):active, .btn-outline-info:not(:disabled):not(.disabled).active,
  .show > .btn-outline-info.dropdown-toggle {
    color: #fff;
    background-color: #2CA8FF;
    border-color: #2CA8FF; }
    .btn-outline-info:not(:disabled):not(.disabled):active:focus, .btn-outline-info:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-info.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(44, 168, 255, 0.5); }

.btn-outline-warning {
  color: #FFB236;
  background-color: transparent;
  background-image: none;
  border-color: #FFB236; }
  .btn-outline-warning:hover {
    color: #fff;
    background-color: #FFB236;
    border-color: #FFB236; }
  .btn-outline-warning:focus, .btn-outline-warning.focus {
    box-shadow: 0 0 0 0.2rem rgba(255, 178, 54, 0.5); }
  .btn-outline-warning.disabled, .btn-outline-warning:disabled {
    color: #FFB236;
    background-color: transparent; }
  .btn-outline-warning:not(:disabled):not(.disabled):active, .btn-outline-warning:not(:disabled):not(.disabled).active,
  .show > .btn-outline-warning.dropdown-toggle {
    color: #fff;
    background-color: #FFB236;
    border-color: #FFB236; }
    .btn-outline-warning:not(:disabled):not(.disabled):active:focus, .btn-outline-warning:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-warning.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(255, 178, 54, 0.5); }

.btn-outline-danger {
  color: #FF3636;
  background-color: transparent;
  background-image: none;
  border-color: #FF3636; }
  .btn-outline-danger:hover {
    color: #fff;
    background-color: #FF3636;
    border-color: #FF3636; }
  .btn-outline-danger:focus, .btn-outline-danger.focus {
    box-shadow: 0 0 0 0.2rem rgba(255, 54, 54, 0.5); }
  .btn-outline-danger.disabled, .btn-outline-danger:disabled {
    color: #FF3636;
    background-color: transparent; }
  .btn-outline-danger:not(:disabled):not(.disabled):active, .btn-outline-danger:not(:disabled):not(.disabled).active,
  .show > .btn-outline-danger.dropdown-toggle {
    color: #fff;
    background-color: #FF3636;
    border-color: #FF3636; }
    .btn-outline-danger:not(:disabled):not(.disabled):active:focus, .btn-outline-danger:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-danger.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(255, 54, 54, 0.5); }

.btn-outline-light {
  color: #FFFFFF;
  background-color: transparent;
  background-image: none;
  border-color: #FFFFFF; }
  .btn-outline-light:hover {
    color: #888;
    background-color: #FFFFFF;
    border-color: #FFFFFF; }
  .btn-outline-light:focus, .btn-outline-light.focus {
    box-shadow: 0 0 0 0.2rem rgba(255, 255, 255, 0.5); }
  .btn-outline-light.disabled, .btn-outline-light:disabled {
    color: #FFFFFF;
    background-color: transparent; }
  .btn-outline-light:not(:disabled):not(.disabled):active, .btn-outline-light:not(:disabled):not(.disabled).active,
  .show > .btn-outline-light.dropdown-toggle {
    color: #888;
    background-color: #FFFFFF;
    border-color: #FFFFFF; }
    .btn-outline-light:not(:disabled):not(.disabled):active:focus, .btn-outline-light:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-light.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(255, 255, 255, 0.5); }

.btn-outline-dark {
  color: #2c2c2c;
  background-color: transparent;
  background-image: none;
  border-color: #2c2c2c; }
  .btn-outline-dark:hover {
    color: #fff;
    background-color: #2c2c2c;
    border-color: #2c2c2c; }
  .btn-outline-dark:focus, .btn-outline-dark.focus {
    box-shadow: 0 0 0 0.2rem rgba(44, 44, 44, 0.5); }
  .btn-outline-dark.disabled, .btn-outline-dark:disabled {
    color: #2c2c2c;
    background-color: transparent; }
  .btn-outline-dark:not(:disabled):not(.disabled):active, .btn-outline-dark:not(:disabled):not(.disabled).active,
  .show > .btn-outline-dark.dropdown-toggle {
    color: #fff;
    background-color: #2c2c2c;
    border-color: #2c2c2c; }
    .btn-outline-dark:not(:disabled):not(.disabled):active:focus, .btn-outline-dark:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-dark.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(44, 44, 44, 0.5); }

.btn-outline-gray {
  color: #EEEEEE;
  background-color: transparent;
  background-image: none;
  border-color: #EEEEEE; }
  .btn-outline-gray:hover {
    color: #888;
    background-color: #EEEEEE;
    border-color: #EEEEEE; }
  .btn-outline-gray:focus, .btn-outline-gray.focus {
    box-shadow: 0 0 0 0.2rem rgba(238, 238, 238, 0.5); }
  .btn-outline-gray.disabled, .btn-outline-gray:disabled {
    color: #EEEEEE;
    background-color: transparent; }
  .btn-outline-gray:not(:disabled):not(.disabled):active, .btn-outline-gray:not(:disabled):not(.disabled).active,
  .show > .btn-outline-gray.dropdown-toggle {
    color: #888;
    background-color: #EEEEEE;
    border-color: #EEEEEE; }
    .btn-outline-gray:not(:disabled):not(.disabled):active:focus, .btn-outline-gray:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-gray.dropdown-toggle:focus {
      box-shadow: 0 0 0 0.2rem rgba(238, 238, 238, 0.5); }

.btn-link {
  font-weight: 400;
  color: #f96332;
  background-color: transparent; }
  .btn-link:hover {
    color: #d83a06;
    text-decoration: none;
    background-color: transparent;
    border-color: transparent; }
  .btn-link:focus, .btn-link.focus {
    text-decoration: none;
    border-color: transparent;
    box-shadow: none; }
  .btn-link:disabled, .btn-link.disabled {
    color: #6c757d; }

.btn-lg, .btn-group-lg > .btn {
  padding: 0.95rem 3rem;
  font-size: 1.09375rem;
  line-height: 1.5;
  border-radius: 0.3rem; }

.btn-sm, .btn-group-sm > .btn {
  padding: 0.25rem 0.8rem;
  font-size: 0.76562rem;
  line-height: 1.5;
  border-radius: 0.2rem; }

.btn-block {
  display: block;
  width: 100%; }
  .btn-block + .btn-block {
    margin-top: 0.5rem; }

input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%; }

.fade {
  opacity: 0;
  transition: opacity 0.15s linear; }
  .fade.show {
    opacity: 1; }

.collapse {
  display: none; }
  .collapse.show {
    display: block; }

tr.collapse.show {
  display: table-row; }

tbody.collapse.show {
  display: table-row-group; }

.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  transition: height 0.35s ease; }

.dropup,
.dropdown {
  position: relative; }

.dropdown-toggle::after {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 0.255em;
  vertical-align: 0.255em;
  content: "";
  border-top: 0.3em solid;
  border-right: 0.3em solid transparent;
  border-bottom: 0;
  border-left: 0.3em solid transparent; }

.dropdown-toggle:empty::after {
  margin-left: 0; }

.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 10rem;
  padding: 0.5rem 0;
  margin: 0.125rem 0 0;
  font-size: 0.875rem;
  color: #292b2c;
  text-align: left;
  list-style: none;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 0.25rem; }

.dropup .dropdown-menu {
  margin-top: 0;
  margin-bottom: 0.125rem; }

.dropup .dropdown-toggle::after {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 0.255em;
  vertical-align: 0.255em;
  content: "";
  border-top: 0;
  border-right: 0.3em solid transparent;
  border-bottom: 0.3em solid;
  border-left: 0.3em solid transparent; }

.dropup .dropdown-toggle:empty::after {
  margin-left: 0; }

.dropright .dropdown-menu {
  margin-top: 0;
  margin-left: 0.125rem; }

.dropright .dropdown-toggle::after {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 0.255em;
  vertical-align: 0.255em;
  content: "";
  border-top: 0.3em solid transparent;
  border-bottom: 0.3em solid transparent;
  border-left: 0.3em solid; }

.dropright .dropdown-toggle:empty::after {
  margin-left: 0; }

.dropright .dropdown-toggle::after {
  vertical-align: 0; }

.dropleft .dropdown-menu {
  margin-top: 0;
  margin-right: 0.125rem; }

.dropleft .dropdown-toggle::after {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 0.255em;
  vertical-align: 0.255em;
  content: ""; }

.dropleft .dropdown-toggle::after {
  display: none; }

.dropleft .dropdown-toggle::before {
  display: inline-block;
  width: 0;
  height: 0;
  margin-right: 0.255em;
  vertical-align: 0.255em;
  content: "";
  border-top: 0.3em solid transparent;
  border-right: 0.3em solid;
  border-bottom: 0.3em solid transparent; }

.dropleft .dropdown-toggle:empty::after {
  margin-left: 0; }

.dropleft .dropdown-toggle::before {
  vertical-align: 0; }

.dropdown-divider {
  height: 0;
  margin: 0.5rem 0;
  overflow: hidden;
  border-top: 1px solid #e9ecef; }

.dropdown-item {
  display: block;
  width: 100%;
  padding: 0.5rem 1.5rem;
  clear: both;
  font-weight: 400;
  color: #212529;
  text-align: inherit;
  white-space: nowrap;
  background-color: transparent;
  border: 0; }
  .dropdown-item:hover, .dropdown-item:focus {
    color: #16181b;
    text-decoration: none;
    background-color: #f8f9fa; }
  .dropdown-item.active, .dropdown-item:active {
    color: #fff;
    text-decoration: none;
    background-color: #f96332; }
  .dropdown-item.disabled, .dropdown-item:disabled {
    color: #6c757d;
    background-color: transparent; }

.dropdown-menu.show {
  display: block; }

.dropdown-header {
  display: block;
  padding: 0.5rem 1.5rem;
  margin-bottom: 0;
  font-size: 0.76562rem;
  color: rgba(41, 43, 44, 0.25);
  white-space: nowrap; }

.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-flex;
  vertical-align: middle; }
  .btn-group > .btn,
  .btn-group-vertical > .btn {
    position: relative;
    flex: 0 1 auto; }
    .btn-group > .btn:hover,
    .btn-group-vertical > .btn:hover {
      z-index: 1; }
    .btn-group > .btn:focus, .btn-group > .btn:active, .btn-group > .btn.active,
    .btn-group-vertical > .btn:focus,
    .btn-group-vertical > .btn:active,
    .btn-group-vertical > .btn.active {
      z-index: 1; }
  .btn-group .btn + .btn,
  .btn-group .btn + .btn-group,
  .btn-group .btn-group + .btn,
  .btn-group .btn-group + .btn-group,
  .btn-group-vertical .btn + .btn,
  .btn-group-vertical .btn + .btn-group,
  .btn-group-vertical .btn-group + .btn,
  .btn-group-vertical .btn-group + .btn-group {
    margin-left: -1px; }

.btn-toolbar {
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-start; }
  .btn-toolbar .input-group {
    width: auto; }

.btn-group > .btn:first-child {
  margin-left: 0; }

.btn-group > .btn:not(:last-child):not(.dropdown-toggle),
.btn-group > .btn-group:not(:last-child) > .btn {
  border-top-right-radius: 0;
  border-bottom-right-radius: 0; }

.btn-group > .btn:not(:first-child),
.btn-group > .btn-group:not(:first-child) > .btn {
  border-top-left-radius: 0;
  border-bottom-left-radius: 0; }

.dropdown-toggle-split {
  padding-right: 0.975rem;
  padding-left: 0.975rem; }
  .dropdown-toggle-split::after {
    margin-left: 0; }

.btn-sm + .dropdown-toggle-split, .btn-group-sm > .btn + .dropdown-toggle-split {
  padding-right: 0.6rem;
  padding-left: 0.6rem; }

.btn-lg + .dropdown-toggle-split, .btn-group-lg > .btn + .dropdown-toggle-split {
  padding-right: 2.25rem;
  padding-left: 2.25rem; }

.btn-group-vertical {
  flex-direction: column;
  align-items: flex-start;
  justify-content: center; }
  .btn-group-vertical .btn,
  .btn-group-vertical .btn-group {
    width: 100%; }
  .btn-group-vertical > .btn + .btn,
  .btn-group-vertical > .btn + .btn-group,
  .btn-group-vertical > .btn-group + .btn,
  .btn-group-vertical > .btn-group + .btn-group {
    margin-top: -1px;
    margin-left: 0; }
  .btn-group-vertical > .btn:not(:last-child):not(.dropdown-toggle),
  .btn-group-vertical > .btn-group:not(:last-child) > .btn {
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 0; }
  .btn-group-vertical > .btn:not(:first-child),
  .btn-group-vertical > .btn-group:not(:first-child) > .btn {
    border-top-left-radius: 0;
    border-top-right-radius: 0; }

.btn-group-toggle > .btn,
.btn-group-toggle > .btn-group > .btn {
  margin-bottom: 0; }
  .btn-group-toggle > .btn input[type="radio"],
  .btn-group-toggle > .btn input[type="checkbox"],
  .btn-group-toggle > .btn-group > .btn input[type="radio"],
  .btn-group-toggle > .btn-group > .btn input[type="checkbox"] {
    position: absolute;
    clip: rect(0, 0, 0, 0);
    pointer-events: none; }

.input-group {
  position: relative;
  display: flex;
  flex-wrap: wrap;
  align-items: stretch;
  width: 100%; }
  .input-group > .form-control,
  .input-group > .custom-select,
  .input-group > .custom-file {
    position: relative;
    flex: 1 1 auto;
    width: 1%;
    margin-bottom: 0; }
    .input-group > .form-control:focus,
    .input-group > .custom-select:focus,
    .input-group > .custom-file:focus {
      z-index: 3; }
    .input-group > .form-control + .form-control,
    .input-group > .form-control + .custom-select,
    .input-group > .form-control + .custom-file,
    .input-group > .custom-select + .form-control,
    .input-group > .custom-select + .custom-select,
    .input-group > .custom-select + .custom-file,
    .input-group > .custom-file + .form-control,
    .input-group > .custom-file + .custom-select,
    .input-group > .custom-file + .custom-file {
      margin-left: -1px; }
  .input-group > .form-control:not(:last-child),
  .input-group > .custom-select:not(:last-child) {
    border-top-right-radius: 0;
    border-bottom-right-radius: 0; }
  .input-group > .form-control:not(:first-child),
  .input-group > .custom-select:not(:first-child) {
    border-top-left-radius: 0;
    border-bottom-left-radius: 0; }
  .input-group > .custom-file {
    display: flex;
    align-items: center; }
    .input-group > .custom-file:not(:last-child) .custom-file-label,
    .input-group > .custom-file:not(:last-child) .custom-file-label::before {
      border-top-right-radius: 0;
      border-bottom-right-radius: 0; }
    .input-group > .custom-file:not(:first-child) .custom-file-label,
    .input-group > .custom-file:not(:first-child) .custom-file-label::before {
      border-top-left-radius: 0;
      border-bottom-left-radius: 0; }

.input-group-prepend,
.input-group-append {
  display: flex; }
  .input-group-prepend .btn,
  .input-group-append .btn {
    position: relative;
    z-index: 2; }
  .input-group-prepend .btn + .btn,
  .input-group-prepend .btn + .input-group-text,
  .input-group-prepend .input-group-text + .input-group-text,
  .input-group-prepend .input-group-text + .btn,
  .input-group-append .btn + .btn,
  .input-group-append .btn + .input-group-text,
  .input-group-append .input-group-text + .input-group-text,
  .input-group-append .input-group-text + .btn {
    margin-left: -1px; }

.input-group-prepend {
  margin-right: -1px; }

.input-group-append {
  margin-left: -1px; }

.input-group-text {
  display: flex;
  align-items: center;
  padding: 0.55rem 1.3rem;
  margin-bottom: 0;
  font-size: 0.875rem;
  font-weight: 400;
  line-height: 1.6;
  color: rgba(41, 43, 44, 0.8);
  text-align: center;
  white-space: nowrap;
  background-color: rgba(255, 255, 255, 0.1);
  border: 1px solid #ced4da;
  border-radius: 2.5rem; }
  .input-group-text input[type="radio"],
  .input-group-text input[type="checkbox"] {
    margin-top: 0; }

.input-group > .input-group-prepend > .btn,
.input-group > .input-group-prepend > .input-group-text,
.input-group > .input-group-append:not(:last-child) > .btn,
.input-group > .input-group-append:not(:last-child) > .input-group-text,
.input-group > .input-group-append:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group > .input-group-append:last-child > .input-group-text:not(:last-child) {
  border-top-right-radius: 0;
  border-bottom-right-radius: 0; }

.input-group > .input-group-append > .btn,
.input-group > .input-group-append > .input-group-text,
.input-group > .input-group-prepend:not(:first-child) > .btn,
.input-group > .input-group-prepend:not(:first-child) > .input-group-text,
.input-group > .input-group-prepend:first-child > .btn:not(:first-child),
.input-group > .input-group-prepend:first-child > .input-group-text:not(:first-child) {
  border-top-left-radius: 0;
  border-bottom-left-radius: 0; }

.custom-control {
  position: relative;
  display: block;
  min-height: 1.6rem;
  padding-left: 1.5rem; }

.custom-control-inline {
  display: inline-flex;
  margin-right: 1rem; }

.custom-control-input {
  position: absolute;
  z-index: -1;
  opacity: 0; }
  .custom-control-input:checked ~ .custom-control-label::before {
    color: #555;
    background-color: transparent; }
  .custom-control-input:focus ~ .custom-control-label::before {
    box-shadow: none; }
  .custom-control-input:active ~ .custom-control-label::before {
    color: #fff;
    background-color: transparent; }
  .custom-control-input:disabled ~ .custom-control-label {
    color: #6c757d; }
    .custom-control-input:disabled ~ .custom-control-label::before {
      background-color: transparent; }

.custom-control-label {
  margin-bottom: 0; }
  .custom-control-label::before {
    position: absolute;
    top: 0.3rem;
    left: 0;
    display: block;
    width: 1rem;
    height: 1rem;
    pointer-events: none;
    content: "";
    user-select: none;
    background-color: transparent; }
  .custom-control-label::after {
    position: absolute;
    top: 0.3rem;
    left: 0;
    display: block;
    width: 1rem;
    height: 1rem;
    content: "";
    background-repeat: no-repeat;
    background-position: center center;
    background-size: 50% 50%; }

.custom-checkbox .custom-control-label::before {
  border-radius: 0.25rem; }

.custom-checkbox .custom-control-input:checked ~ .custom-control-label::before {
  background-color: transparent; }

.custom-checkbox .custom-control-input:checked ~ .custom-control-label::after {
  background-image: none; }

.custom-checkbox .custom-control-input:indeterminate ~ .custom-control-label::before {
  background-color: transparent; }

.custom-checkbox .custom-control-input:indeterminate ~ .custom-control-label::after {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 4 4'%3E%3Cpath stroke='%23555' d='M0 2h4'/%3E%3C/svg%3E"); }

.custom-checkbox .custom-control-input:disabled:checked ~ .custom-control-label::before {
  background-color: transparent; }

.custom-checkbox .custom-control-input:disabled:indeterminate ~ .custom-control-label::before {
  background-color: transparent; }

.custom-radio .custom-control-label::before {
  border-radius: 50%; }

.custom-radio .custom-control-input:checked ~ .custom-control-label::before {
  background-color: transparent; }

.custom-radio .custom-control-input:checked ~ .custom-control-label::after {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='-4 -4 8 8'%3E%3Ccircle r='2' fill='#555'/%3E%3C/svg%3E"); }

.custom-radio .custom-control-input:disabled:checked ~ .custom-control-label::before {
  background-color: transparent; }

.custom-select {
  display: inline-block;
  width: 100%;
  height: calc(2.29rem + 2px);
  padding: 0.375rem 1.75rem 0.375rem 0.75rem;
  line-height: 1.6;
  color: inherit;
  vertical-align: middle;
  background: #fff url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 4 5'%3E%3Cpath fill='%23343a40' d='M2 0L0 2h4zm0 5L0 3h4z'/%3E%3C/svg%3E") no-repeat right 0.75rem center;
  background-size: 8px 10px;
  border: 1px solid #ced4da;
  border-radius: 0.25rem;
  appearance: none; }
  .custom-select:focus {
    border-color: #fdc1ae;
    outline: 0;
    box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.075), 0 0 5px rgba(253, 193, 174, 0.5); }
    .custom-select:focus::-ms-value {
      color: inherit;
      background-color: rgba(255, 255, 255, 0.1); }
  .custom-select[multiple], .custom-select[size]:not([size="1"]) {
    height: auto;
    padding-right: 0.75rem;
    background-image: none; }
  .custom-select:disabled {
    color: #6c757d;
    background-color: #e9ecef; }
  .custom-select::-ms-expand {
    opacity: 0; }

.custom-select-sm {
  height: calc(1.64844rem + 2px);
  padding-top: 0.375rem;
  padding-bottom: 0.375rem;
  font-size: 75%; }

.custom-select-lg {
  height: calc(3.54062rem + 2px);
  padding-top: 0.375rem;
  padding-bottom: 0.375rem;
  font-size: 125%; }

.custom-file {
  position: relative;
  display: inline-block;
  width: 100%;
  height: calc(2.29rem + 2px);
  margin-bottom: 0; }

.custom-file-input {
  position: relative;
  z-index: 2;
  width: 100%;
  height: calc(2.29rem + 2px);
  margin: 0;
  opacity: 0; }
  .custom-file-input:focus ~ .custom-file-control {
    border-color: #fdc1ae;
    box-shadow: 0 0 0 0.2rem rgba(249, 99, 50, 0.25); }
    .custom-file-input:focus ~ .custom-file-control::before {
      border-color: #fdc1ae; }
  .custom-file-input:lang(en) ~ .custom-file-label::after {
    content: "Browse"; }

.custom-file-label {
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
  z-index: 1;
  height: calc(2.29rem + 2px);
  padding: 0.55rem 1.3rem;
  line-height: 1.6;
  color: inherit;
  background-color: rgba(255, 255, 255, 0.1);
  border: 1px solid #ced4da;
  border-radius: 2.5rem; }
  .custom-file-label::after {
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    z-index: 3;
    display: block;
    height: calc(calc(2.29rem + 2px) - 1px * 2);
    padding: 0.55rem 1.3rem;
    line-height: 1.6;
    color: inherit;
    content: "Browse";
    background-color: rgba(255, 255, 255, 0.1);
    border-left: 1px solid #ced4da;
    border-radius: 0 2.5rem 2.5rem 0; }

.nav {
  display: flex;
  flex-wrap: wrap;
  padding-left: 0;
  margin-bottom: 0;
  list-style: none; }

.nav-link {
  display: block;
  padding: 0.7rem 1.4rem; }
  .nav-link:hover, .nav-link:focus {
    text-decoration: none; }
  .nav-link.disabled {
    color: #6c757d; }

.nav-tabs {
  border-bottom: 0px solid #dee2e6; }
  .nav-tabs .nav-item {
    margin-bottom: 0px; }
  .nav-tabs .nav-link {
    border: 0px solid transparent;
    border-top-left-radius: 0.25rem;
    border-top-right-radius: 0.25rem; }
    .nav-tabs .nav-link:hover, .nav-tabs .nav-link:focus {
      border-color: #e9ecef #e9ecef #dee2e6; }
    .nav-tabs .nav-link.disabled {
      color: #6c757d;
      background-color: transparent;
      border-color: transparent; }
  .nav-tabs .nav-link.active,
  .nav-tabs .nav-item.show .nav-link {
    color: #495057;
    background-color: white;
    border-color: #dee2e6 #dee2e6 white; }
  .nav-tabs .dropdown-menu {
    margin-top: 0px;
    border-top-left-radius: 0;
    border-top-right-radius: 0; }

.nav-pills .nav-link {
  border-radius: 2.8rem; }

.nav-pills .nav-link.active,
.nav-pills .show > .nav-link {
  color: #fff;
  background-color: #f96332; }

.nav-fill .nav-item {
  flex: 1 1 auto;
  text-align: center; }

.nav-justified .nav-item {
  flex-basis: 0;
  flex-grow: 1;
  text-align: center; }

.tab-content > .tab-pane {
  display: none; }

.tab-content > .active {
  display: block; }

.navbar {
  position: relative;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  padding: 9px 1rem; }
  .navbar > .container,
  .navbar > .container-fluid {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between; }

.navbar-brand {
  display: inline-block;
  padding-top: 0.805rem;
  padding-bottom: 0.805rem;
  margin-right: 1rem;
  font-size: 0.74375rem;
  line-height: inherit;
  white-space: nowrap; }
  .navbar-brand:hover, .navbar-brand:focus {
    text-decoration: none; }

.navbar-nav {
  display: flex;
  flex-direction: column;
  padding-left: 0;
  margin-bottom: 0;
  list-style: none; }
  .navbar-nav .nav-link {
    padding-right: 0;
    padding-left: 0; }
  .navbar-nav .dropdown-menu {
    position: static;
    float: none; }

.navbar-text {
  display: inline-block;
  padding-top: 0.7rem;
  padding-bottom: 0.7rem; }

.navbar-collapse {
  flex-basis: 100%;
  flex-grow: 1;
  align-items: center; }

.navbar-toggler {
  padding: 0.25rem 0.75rem;
  font-size: 1.09375rem;
  line-height: 1;
  background-color: transparent;
  border: 1px solid transparent;
  border-radius: 0.25rem; }
  .navbar-toggler:hover, .navbar-toggler:focus {
    text-decoration: none; }
  .navbar-toggler:not(:disabled):not(.disabled) {
    cursor: pointer; }

.navbar-toggler-icon {
  display: inline-block;
  width: 1.5em;
  height: 1.5em;
  vertical-align: middle;
  content: "";
  background: no-repeat center center;
  background-size: 100% 100%; }

@media (max-width: 575.98px) {
  .navbar-expand-sm > .container,
  .navbar-expand-sm > .container-fluid {
    padding-right: 0;
    padding-left: 0; } }

@media (min-width: 576px) {
  .navbar-expand-sm {
    flex-flow: row nowrap;
    justify-content: flex-start; }
    .navbar-expand-sm .navbar-nav {
      flex-direction: row; }
      .navbar-expand-sm .navbar-nav .dropdown-menu {
        position: absolute; }
      .navbar-expand-sm .navbar-nav .dropdown-menu-right {
        right: 0;
        left: auto; }
      .navbar-expand-sm .navbar-nav .nav-link {
        padding-right: 0.65rem;
        padding-left: 0.65rem; }
    .navbar-expand-sm > .container,
    .navbar-expand-sm > .container-fluid {
      flex-wrap: nowrap; }
    .navbar-expand-sm .navbar-collapse {
      display: flex !important;
      flex-basis: auto; }
    .navbar-expand-sm .navbar-toggler {
      display: none; }
    .navbar-expand-sm .dropup .dropdown-menu {
      top: auto;
      bottom: 100%; } }

@media (max-width: 767.98px) {
  .navbar-expand-md > .container,
  .navbar-expand-md > .container-fluid {
    padding-right: 0;
    padding-left: 0; } }

@media (min-width: 768px) {
  .navbar-expand-md {
    flex-flow: row nowrap;
    justify-content: flex-start; }
    .navbar-expand-md .navbar-nav {
      flex-direction: row; }
      .navbar-expand-md .navbar-nav .dropdown-menu {
        position: absolute; }
      .navbar-expand-md .navbar-nav .dropdown-menu-right {
        right: 0;
        left: auto; }
      .navbar-expand-md .navbar-nav .nav-link {
        padding-right: 0.65rem;
        padding-left: 0.65rem; }
    .navbar-expand-md > .container,
    .navbar-expand-md > .container-fluid {
      flex-wrap: nowrap; }
    .navbar-expand-md .navbar-collapse {
      display: flex !important;
      flex-basis: auto; }
    .navbar-expand-md .navbar-toggler {
      display: none; }
    .navbar-expand-md .dropup .dropdown-menu {
      top: auto;
      bottom: 100%; } }

@media (max-width: 991.98px) {
  .navbar-expand-lg > .container,
  .navbar-expand-lg > .container-fluid {
    padding-right: 0;
    padding-left: 0; } }

@media (min-width: 992px) {
  .navbar-expand-lg {
    flex-flow: row nowrap;
    justify-content: flex-start; }
    .navbar-expand-lg .navbar-nav {
      flex-direction: row; }
      .navbar-expand-lg .navbar-nav .dropdown-menu {
        position: absolute; }
      .navbar-expand-lg .navbar-nav .dropdown-menu-right {
        right: 0;
        left: auto; }
      .navbar-expand-lg .navbar-nav .nav-link {
        padding-right: 0.65rem;
        padding-left: 0.65rem; }
    .navbar-expand-lg > .container,
    .navbar-expand-lg > .container-fluid {
      flex-wrap: nowrap; }
    .navbar-expand-lg .navbar-collapse {
      display: flex !important;
      flex-basis: auto; }
    .navbar-expand-lg .navbar-toggler {
      display: none; }
    .navbar-expand-lg .dropup .dropdown-menu {
      top: auto;
      bottom: 100%; } }

@media (max-width: 1199.98px) {
  .navbar-expand-xl > .container,
  .navbar-expand-xl > .container-fluid {
    padding-right: 0;
    padding-left: 0; } }

@media (min-width: 1200px) {
  .navbar-expand-xl {
    flex-flow: row nowrap;
    justify-content: flex-start; }
    .navbar-expand-xl .navbar-nav {
      flex-direction: row; }
      .navbar-expand-xl .navbar-nav .dropdown-menu {
        position: absolute; }
      .navbar-expand-xl .navbar-nav .dropdown-menu-right {
        right: 0;
        left: auto; }
      .navbar-expand-xl .navbar-nav .nav-link {
        padding-right: 0.65rem;
        padding-left: 0.65rem; }
    .navbar-expand-xl > .container,
    .navbar-expand-xl > .container-fluid {
      flex-wrap: nowrap; }
    .navbar-expand-xl .navbar-collapse {
      display: flex !important;
      flex-basis: auto; }
    .navbar-expand-xl .navbar-toggler {
      display: none; }
    .navbar-expand-xl .dropup .dropdown-menu {
      top: auto;
      bottom: 100%; } }

.navbar-expand {
  flex-flow: row nowrap;
  justify-content: flex-start; }
  .navbar-expand > .container,
  .navbar-expand > .container-fluid {
    padding-right: 0;
    padding-left: 0; }
  .navbar-expand .navbar-nav {
    flex-direction: row; }
    .navbar-expand .navbar-nav .dropdown-menu {
      position: absolute; }
    .navbar-expand .navbar-nav .dropdown-menu-right {
      right: 0;
      left: auto; }
    .navbar-expand .navbar-nav .nav-link {
      padding-right: 0.65rem;
      padding-left: 0.65rem; }
  .navbar-expand > .container,
  .navbar-expand > .container-fluid {
    flex-wrap: nowrap; }
  .navbar-expand .navbar-collapse {
    display: flex !important;
    flex-basis: auto; }
  .navbar-expand .navbar-toggler {
    display: none; }
  .navbar-expand .dropup .dropdown-menu {
    top: auto;
    bottom: 100%; }

.navbar-light .navbar-brand {
  color: rgba(0, 0, 0, 0.9); }
  .navbar-light .navbar-brand:hover, .navbar-light .navbar-brand:focus {
    color: rgba(0, 0, 0, 0.9); }

.navbar-light .navbar-nav .nav-link {
  color: rgba(0, 0, 0, 0.5); }
  .navbar-light .navbar-nav .nav-link:hover, .navbar-light .navbar-nav .nav-link:focus {
    color: rgba(0, 0, 0, 0.7); }
  .navbar-light .navbar-nav .nav-link.disabled {
    color: rgba(0, 0, 0, 0.3); }

.navbar-light .navbar-nav .show > .nav-link,
.navbar-light .navbar-nav .active > .nav-link,
.navbar-light .navbar-nav .nav-link.show,
.navbar-light .navbar-nav .nav-link.active {
  color: rgba(0, 0, 0, 0.9); }

.navbar-light .navbar-toggler {
  color: rgba(0, 0, 0, 0.5);
  border-color: rgba(0, 0, 0, 0.1); }

.navbar-light .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(0, 0, 0, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E"); }

.navbar-light .navbar-text {
  color: rgba(0, 0, 0, 0.5); }
  .navbar-light .navbar-text a {
    color: rgba(0, 0, 0, 0.9); }
    .navbar-light .navbar-text a:hover, .navbar-light .navbar-text a:focus {
      color: rgba(0, 0, 0, 0.9); }

.navbar-dark .navbar-brand {
  color: #fff; }
  .navbar-dark .navbar-brand:hover, .navbar-dark .navbar-brand:focus {
    color: #fff; }

.navbar-dark .navbar-nav .nav-link {
  color: white; }
  .navbar-dark .navbar-nav .nav-link:hover, .navbar-dark .navbar-nav .nav-link:focus {
    color: white; }
  .navbar-dark .navbar-nav .nav-link.disabled {
    color: rgba(255, 255, 255, 0.25); }

.navbar-dark .navbar-nav .show > .nav-link,
.navbar-dark .navbar-nav .active > .nav-link,
.navbar-dark .navbar-nav .nav-link.show,
.navbar-dark .navbar-nav .nav-link.active {
  color: #fff; }

.navbar-dark .navbar-toggler {
  color: white;
  border-color: rgba(255, 255, 255, 0.1); }

.navbar-dark .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='white' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E"); }

.navbar-dark .navbar-text {
  color: white; }
  .navbar-dark .navbar-text a {
    color: #fff; }
    .navbar-dark .navbar-text a:hover, .navbar-dark .navbar-text a:focus {
      color: #fff; }

.card {
  position: relative;
  display: flex;
  flex-direction: column;
  min-width: 0;
  word-wrap: break-word;
  background-color: #fff;
  background-clip: border-box;
  border: 0px solid rgba(0, 0, 0, 0.125);
  border-radius: 0.25rem; }
  .card > hr {
    margin-right: 0;
    margin-left: 0; }
  .card > .list-group:first-child .list-group-item:first-child {
    border-top-left-radius: 0.25rem;
    border-top-right-radius: 0.25rem; }
  .card > .list-group:last-child .list-group-item:last-child {
    border-bottom-right-radius: 0.25rem;
    border-bottom-left-radius: 0.25rem; }

.card-body {
  flex: 1 1 auto;
  padding: 1.25rem; }

.card-title {
  margin-bottom: 0.75rem; }

.card-subtitle {
  margin-top: -0.375rem;
  margin-bottom: 0; }

.card-text:last-child {
  margin-bottom: 0; }

.card-link:hover {
  text-decoration: none; }

.card-link + .card-link {
  margin-left: 1.25rem; }

.card-header {
  padding: 0.75rem 1.25rem;
  margin-bottom: 0;
  background-color: rgba(0, 0, 0, 0.03);
  border-bottom: 0px solid rgba(0, 0, 0, 0.125); }
  .card-header:first-child {
    border-radius: calc(0.25rem - 0px) calc(0.25rem - 0px) 0 0; }
  .card-header + .list-group .list-group-item:first-child {
    border-top: 0; }

.card-footer {
  padding: 0.75rem 1.25rem;
  background-color: rgba(0, 0, 0, 0.03);
  border-top: 0px solid rgba(0, 0, 0, 0.125); }
  .card-footer:last-child {
    border-radius: 0 0 calc(0.25rem - 0px) calc(0.25rem - 0px); }

.card-header-tabs {
  margin-right: -0.625rem;
  margin-bottom: -0.75rem;
  margin-left: -0.625rem;
  border-bottom: 0; }

.card-header-pills {
  margin-right: -0.625rem;
  margin-left: -0.625rem; }

.card-img-overlay {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  padding: 1.25rem; }

.card-img {
  width: 100%;
  border-radius: calc(0.25rem - 0px); }

.card-img-top {
  width: 100%;
  border-top-left-radius: calc(0.25rem - 0px);
  border-top-right-radius: calc(0.25rem - 0px); }

.card-img-bottom {
  width: 100%;
  border-bottom-right-radius: calc(0.25rem - 0px);
  border-bottom-left-radius: calc(0.25rem - 0px); }

.card-deck {
  display: flex;
  flex-direction: column; }
  .card-deck .card {
    margin-bottom: 15px; }
  @media (min-width: 576px) {
    .card-deck {
      flex-flow: row wrap;
      margin-right: -15px;
      margin-left: -15px; }
      .card-deck .card {
        display: flex;
        flex: 1 0 0%;
        flex-direction: column;
        margin-right: 15px;
        margin-bottom: 0;
        margin-left: 15px; } }

.card-group {
  display: flex;
  flex-direction: column; }
  .card-group > .card {
    margin-bottom: 15px; }
  @media (min-width: 576px) {
    .card-group {
      flex-flow: row wrap; }
      .card-group > .card {
        flex: 1 0 0%;
        margin-bottom: 0; }
        .card-group > .card + .card {
          margin-left: 0;
          border-left: 0; }
        .card-group > .card:first-child {
          border-top-right-radius: 0;
          border-bottom-right-radius: 0; }
          .card-group > .card:first-child .card-img-top,
          .card-group > .card:first-child .card-header {
            border-top-right-radius: 0; }
          .card-group > .card:first-child .card-img-bottom,
          .card-group > .card:first-child .card-footer {
            border-bottom-right-radius: 0; }
        .card-group > .card:last-child {
          border-top-left-radius: 0;
          border-bottom-left-radius: 0; }
          .card-group > .card:last-child .card-img-top,
          .card-group > .card:last-child .card-header {
            border-top-left-radius: 0; }
          .card-group > .card:last-child .card-img-bottom,
          .card-group > .card:last-child .card-footer {
            border-bottom-left-radius: 0; }
        .card-group > .card:only-child {
          border-radius: 0.25rem; }
          .card-group > .card:only-child .card-img-top,
          .card-group > .card:only-child .card-header {
            border-top-left-radius: 0.25rem;
            border-top-right-radius: 0.25rem; }
          .card-group > .card:only-child .card-img-bottom,
          .card-group > .card:only-child .card-footer {
            border-bottom-right-radius: 0.25rem;
            border-bottom-left-radius: 0.25rem; }
        .card-group > .card:not(:first-child):not(:last-child):not(:only-child) {
          border-radius: 0; }
          .card-group > .card:not(:first-child):not(:last-child):not(:only-child) .card-img-top,
          .card-group > .card:not(:first-child):not(:last-child):not(:only-child) .card-img-bottom,
          .card-group > .card:not(:first-child):not(:last-child):not(:only-child) .card-header,
          .card-group > .card:not(:first-child):not(:last-child):not(:only-child) .card-footer {
            border-radius: 0; } }

.card-columns .card {
  margin-bottom: 0.75rem; }

@media (min-width: 576px) {
  .card-columns {
    column-count: 3;
    column-gap: 1.25rem; }
    .card-columns .card {
      display: inline-block;
      width: 100%; } }

.breadcrumb {
  display: flex;
  flex-wrap: wrap;
  padding: 0.75rem 1rem;
  margin-bottom: 1rem;
  list-style: none;
  background-color: #e9ecef;
  border-radius: 0.25rem; }

.breadcrumb-item + .breadcrumb-item::before {
  display: inline-block;
  padding-right: 0.5rem;
  padding-left: 0.5rem;
  color: #6c757d;
  content: "/"; }

.breadcrumb-item + .breadcrumb-item:hover::before {
  text-decoration: underline; }

.breadcrumb-item + .breadcrumb-item:hover::before {
  text-decoration: none; }

.breadcrumb-item.active {
  color: #6c757d; }

.pagination {
  display: flex;
  padding-left: 0;
  list-style: none;
  border-radius: 0.25rem; }

.page-link {
  position: relative;
  display: block;
  padding: 0.5rem 0.75rem;
  margin-left: 0px;
  line-height: 1.25;
  color: #f96332;
  background-color: #fff;
  border: 0px solid #dee2e6; }
  .page-link:hover {
    color: #d83a06;
    text-decoration: none;
    background-color: #e9ecef;
    border-color: #dee2e6; }
  .page-link:focus {
    z-index: 2;
    outline: 0;
    box-shadow: 0 0 0 0.2rem rgba(249, 99, 50, 0.25); }
  .page-link:not(:disabled):not(.disabled) {
    cursor: pointer; }

.page-item:first-child .page-link {
  margin-left: 0;
  border-top-left-radius: 0.25rem;
  border-bottom-left-radius: 0.25rem; }

.page-item:last-child .page-link {
  border-top-right-radius: 0.25rem;
  border-bottom-right-radius: 0.25rem; }

.page-item.active .page-link {
  z-index: 1;
  color: #fff;
  background-color: #f96332;
  border-color: #f96332; }

.page-item.disabled .page-link {
  color: #6c757d;
  pointer-events: none;
  cursor: auto;
  background-color: #fff;
  border-color: #dee2e6; }

.pagination-lg .page-link {
  padding: 0.75rem 1.5rem;
  font-size: 1.09375rem;
  line-height: 1.5; }

.pagination-lg .page-item:first-child .page-link {
  border-top-left-radius: 0.3rem;
  border-bottom-left-radius: 0.3rem; }

.pagination-lg .page-item:last-child .page-link {
  border-top-right-radius: 0.3rem;
  border-bottom-right-radius: 0.3rem; }

.pagination-sm .page-link {
  padding: 0.25rem 0.5rem;
  font-size: 0.76562rem;
  line-height: 1.5; }

.pagination-sm .page-item:first-child .page-link {
  border-top-left-radius: 0.2rem;
  border-bottom-left-radius: 0.2rem; }

.pagination-sm .page-item:last-child .page-link {
  border-top-right-radius: 0.2rem;
  border-bottom-right-radius: 0.2rem; }

.badge {
  display: inline-block;
  padding: 0.25em 0.4em;
  font-size: 0.7142em;
  font-weight: 700;
  line-height: 1;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: 0.25rem; }
  .badge:empty {
    display: none; }

.btn .badge {
  position: relative;
  top: -1px; }

.badge-pill {
  padding-right: 0.5rem;
  padding-left: 0.5rem;
  border-radius: 10rem; }

.badge-primary {
  color: #fff;
  background-color: #f96332; }
  .badge-primary[href]:hover, .badge-primary[href]:focus {
    color: #fff;
    text-decoration: none;
    background-color: #f14107; }

.badge-secondary {
  color: #fff;
  background-color: #888; }
  .badge-secondary[href]:hover, .badge-secondary[href]:focus {
    color: #fff;
    text-decoration: none;
    background-color: #6f6f6f; }

.badge-success {
  color: #fff;
  background-color: #18ce0f; }
  .badge-success[href]:hover, .badge-success[href]:focus {
    color: #fff;
    text-decoration: none;
    background-color: #129e0c; }

.badge-info {
  color: #fff;
  background-color: #2CA8FF; }
  .badge-info[href]:hover, .badge-info[href]:focus {
    color: #fff;
    text-decoration: none;
    background-color: #0092f8; }

.badge-warning {
  color: #fff;
  background-color: #FFB236; }
  .badge-warning[href]:hover, .badge-warning[href]:focus {
    color: #fff;
    text-decoration: none;
    background-color: #ff9e03; }

.badge-danger {
  color: #fff;
  background-color: #FF3636; }
  .badge-danger[href]:hover, .badge-danger[href]:focus {
    color: #fff;
    text-decoration: none;
    background-color: #ff0303; }

.badge-light {
  color: #888;
  background-color: #FFFFFF; }
  .badge-light[href]:hover, .badge-light[href]:focus {
    color: #888;
    text-decoration: none;
    background-color: #e6e6e6; }

.badge-dark {
  color: #fff;
  background-color: #2c2c2c; }
  .badge-dark[href]:hover, .badge-dark[href]:focus {
    color: #fff;
    text-decoration: none;
    background-color: #131313; }

.badge-gray {
  color: #888;
  background-color: #EEEEEE; }
  .badge-gray[href]:hover, .badge-gray[href]:focus {
    color: #888;
    text-decoration: none;
    background-color: #d5d5d5; }

.jumbotron {
  padding: 2rem 1rem;
  margin-bottom: 2rem;
  background-color: #e9ecef;
  border-radius: 0.3rem; }
  @media (min-width: 576px) {
    .jumbotron {
      padding: 4rem 2rem; } }

.jumbotron-fluid {
  padding-right: 0;
  padding-left: 0;
  border-radius: 0; }

.alert {
  position: relative;
  padding: 0.75rem 1.25rem;
  margin-bottom: 1rem;
  border: 1px solid transparent;
  border-radius: 0.25rem; }

.alert-heading {
  color: inherit; }

.alert-link {
  font-weight: 700; }

.alert-dismissible {
  padding-right: 3.8125rem; }
  .alert-dismissible .close {
    position: absolute;
    top: 0;
    right: 0;
    padding: 0.75rem 1.25rem;
    color: inherit; }

.alert-primary {
  color: #81331a;
  background-color: #fee0d6;
  border-color: #fdd3c6; }
  .alert-primary hr {
    border-top-color: #fcc0ad; }
  .alert-primary .alert-link {
    color: #572211; }

.alert-secondary {
  color: #474747;
  background-color: #e7e7e7;
  border-color: #dedede; }
  .alert-secondary hr {
    border-top-color: #d1d1d1; }
  .alert-secondary .alert-link {
    color: #2e2e2e; }

.alert-success {
  color: #0c6b08;
  background-color: #d1f5cf;
  border-color: #bef1bc; }
  .alert-success hr {
    border-top-color: #aaeda7; }
  .alert-success .alert-link {
    color: #073c04; }

.alert-info {
  color: #175785;
  background-color: #d5eeff;
  border-color: #c4e7ff; }
  .alert-info hr {
    border-top-color: #abddff; }
  .alert-info .alert-link {
    color: #0f3b5a; }

.alert-warning {
  color: #855d1c;
  background-color: #fff0d7;
  border-color: #ffe9c7; }
  .alert-warning hr {
    border-top-color: #ffdfae; }
  .alert-warning .alert-link {
    color: #5b4013; }

.alert-danger {
  color: #851c1c;
  background-color: #ffd7d7;
  border-color: #ffc7c7; }
  .alert-danger hr {
    border-top-color: #ffaeae; }
  .alert-danger .alert-link {
    color: #5b1313; }

.alert-light {
  color: #858585;
  background-color: white;
  border-color: white; }
  .alert-light hr {
    border-top-color: #f2f2f2; }
  .alert-light .alert-link {
    color: #6c6c6c; }

.alert-dark {
  color: #171717;
  background-color: #d5d5d5;
  border-color: #c4c4c4; }
  .alert-dark hr {
    border-top-color: #b7b7b7; }
  .alert-dark .alert-link {
    color: black; }

.alert-gray {
  color: #7c7c7c;
  background-color: #fcfcfc;
  border-color: #fafafa; }
  .alert-gray hr {
    border-top-color: #ededed; }
  .alert-gray .alert-link {
    color: #636363; }

@keyframes progress-bar-stripes {
  from {
    background-position: 1px 0; }
  to {
    background-position: 0 0; } }

.progress {
  display: flex;
  height: 1px;
  overflow: hidden;
  font-size: 0.65625rem;
  background-color: #e9ecef;
  border-radius: 0.25rem; }

.progress-bar {
  display: flex;
  flex-direction: column;
  justify-content: center;
  color: #fff;
  text-align: center;
  background-color: #f96332;
  transition: width 0.6s ease; }

.progress-bar-striped {
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 1px 1px; }

.progress-bar-animated {
  animation: progress-bar-stripes 1s linear infinite; }

.media {
  display: flex;
  align-items: flex-start; }

.media-body {
  flex: 1; }

.list-group {
  display: flex;
  flex-direction: column;
  padding-left: 0;
  margin-bottom: 0; }

.list-group-item-action {
  width: 100%;
  color: #495057;
  text-align: inherit; }
  .list-group-item-action:hover, .list-group-item-action:focus {
    color: #495057;
    text-decoration: none;
    background-color: #f8f9fa; }
  .list-group-item-action:active {
    color: #292b2c;
    background-color: #e9ecef; }

.list-group-item {
  position: relative;
  display: block;
  padding: 0.75rem 1.25rem;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid rgba(0, 0, 0, 0.125); }
  .list-group-item:first-child {
    border-top-left-radius: 0.25rem;
    border-top-right-radius: 0.25rem; }
  .list-group-item:last-child {
    margin-bottom: 0;
    border-bottom-right-radius: 0.25rem;
    border-bottom-left-radius: 0.25rem; }
  .list-group-item:hover, .list-group-item:focus {
    z-index: 1;
    text-decoration: none; }
  .list-group-item.disabled, .list-group-item:disabled {
    color: #6c757d;
    background-color: #fff; }
  .list-group-item.active {
    z-index: 2;
    color: #fff;
    background-color: #f96332;
    border-color: #f96332; }

.list-group-flush .list-group-item {
  border-right: 0;
  border-left: 0;
  border-radius: 0; }

.list-group-flush:first-child .list-group-item:first-child {
  border-top: 0; }

.list-group-flush:last-child .list-group-item:last-child {
  border-bottom: 0; }

.list-group-item-primary {
  color: #81331a;
  background-color: #fdd3c6; }
  .list-group-item-primary.list-group-item-action:hover, .list-group-item-primary.list-group-item-action:focus {
    color: #81331a;
    background-color: #fcc0ad; }
  .list-group-item-primary.list-group-item-action.active {
    color: #fff;
    background-color: #81331a;
    border-color: #81331a; }

.list-group-item-secondary {
  color: #474747;
  background-color: #dedede; }
  .list-group-item-secondary.list-group-item-action:hover, .list-group-item-secondary.list-group-item-action:focus {
    color: #474747;
    background-color: #d1d1d1; }
  .list-group-item-secondary.list-group-item-action.active {
    color: #fff;
    background-color: #474747;
    border-color: #474747; }

.list-group-item-success {
  color: #0c6b08;
  background-color: #bef1bc; }
  .list-group-item-success.list-group-item-action:hover, .list-group-item-success.list-group-item-action:focus {
    color: #0c6b08;
    background-color: #aaeda7; }
  .list-group-item-success.list-group-item-action.active {
    color: #fff;
    background-color: #0c6b08;
    border-color: #0c6b08; }

.list-group-item-info {
  color: #175785;
  background-color: #c4e7ff; }
  .list-group-item-info.list-group-item-action:hover, .list-group-item-info.list-group-item-action:focus {
    color: #175785;
    background-color: #abddff; }
  .list-group-item-info.list-group-item-action.active {
    color: #fff;
    background-color: #175785;
    border-color: #175785; }

.list-group-item-warning {
  color: #855d1c;
  background-color: #ffe9c7; }
  .list-group-item-warning.list-group-item-action:hover, .list-group-item-warning.list-group-item-action:focus {
    color: #855d1c;
    background-color: #ffdfae; }
  .list-group-item-warning.list-group-item-action.active {
    color: #fff;
    background-color: #855d1c;
    border-color: #855d1c; }

.list-group-item-danger {
  color: #851c1c;
  background-color: #ffc7c7; }
  .list-group-item-danger.list-group-item-action:hover, .list-group-item-danger.list-group-item-action:focus {
    color: #851c1c;
    background-color: #ffaeae; }
  .list-group-item-danger.list-group-item-action.active {
    color: #fff;
    background-color: #851c1c;
    border-color: #851c1c; }

.list-group-item-light {
  color: #858585;
  background-color: white; }
  .list-group-item-light.list-group-item-action:hover, .list-group-item-light.list-group-item-action:focus {
    color: #858585;
    background-color: #f2f2f2; }
  .list-group-item-light.list-group-item-action.active {
    color: #fff;
    background-color: #858585;
    border-color: #858585; }

.list-group-item-dark {
  color: #171717;
  background-color: #c4c4c4; }
  .list-group-item-dark.list-group-item-action:hover, .list-group-item-dark.list-group-item-action:focus {
    color: #171717;
    background-color: #b7b7b7; }
  .list-group-item-dark.list-group-item-action.active {
    color: #fff;
    background-color: #171717;
    border-color: #171717; }

.list-group-item-gray {
  color: #7c7c7c;
  background-color: #fafafa; }
  .list-group-item-gray.list-group-item-action:hover, .list-group-item-gray.list-group-item-action:focus {
    color: #7c7c7c;
    background-color: #ededed; }
  .list-group-item-gray.list-group-item-action.active {
    color: #fff;
    background-color: #7c7c7c;
    border-color: #7c7c7c; }

.close {
  float: right;
  font-size: 1.3125rem;
  font-weight: 700;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: .5; }
  .close:hover, .close:focus {
    color: #000;
    text-decoration: none;
    opacity: .75; }
  .close:not(:disabled):not(.disabled) {
    cursor: pointer; }

button.close {
  padding: 0;
  background-color: transparent;
  border: 0;
  -webkit-appearance: none; }

.modal-open {
  overflow: hidden; }

.modal {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  display: none;
  overflow: hidden;
  outline: 0; }
  .modal-open .modal {
    overflow-x: hidden;
    overflow-y: auto; }

.modal-dialog {
  position: relative;
  width: auto;
  margin: 0.5rem;
  pointer-events: none; }
  .modal.fade .modal-dialog {
    transition: transform 0.3s ease-out;
    transform: translate(0, -25%); }
  .modal.show .modal-dialog {
    transform: translate(0, 0); }

.modal-dialog-centered {
  display: flex;
  align-items: center;
  min-height: calc(100% - (0.5rem * 2)); }

.modal-content {
  position: relative;
  display: flex;
  flex-direction: column;
  width: 100%;
  pointer-events: auto;
  background-color: #fff;
  background-clip: padding-box;
  border: 0px solid rgba(0, 0, 0, 0.2);
  border-radius: 0.3rem;
  outline: 0; }

.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000; }
  .modal-backdrop.fade {
    opacity: 0; }
  .modal-backdrop.show {
    opacity: 0.15; }

.modal-header {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  padding: 1.5rem;
  border-bottom: 0px solid #e9ecef;
  border-top-left-radius: 0.3rem;
  border-top-right-radius: 0.3rem; }
  .modal-header .close {
    padding: 1.5rem;
    margin: -1.5rem -1.5rem -1.5rem auto; }

.modal-title {
  margin-bottom: 0;
  line-height: 1.6; }

.modal-body {
  position: relative;
  flex: 1 1 auto;
  padding: 1.2rem; }

.modal-footer {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  padding: 1.2rem;
  border-top: 0px solid #e9ecef; }
  .modal-footer > :not(:first-child) {
    margin-left: .25rem; }
  .modal-footer > :not(:last-child) {
    margin-right: .25rem; }

.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll; }

@media (min-width: 576px) {
  .modal-dialog {
    max-width: 500px;
    margin: 1.75rem auto; }
  .modal-dialog-centered {
    min-height: calc(100% - (1.75rem * 2)); }
  .modal-sm {
    max-width: 255px; } }

@media (min-width: 992px) {
  .modal-lg {
    max-width: 800px; } }

.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  margin: 0;
  font-family: Montserrat;
  font-style: normal;
  font-weight: 400;
  line-height: 1.6;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  letter-spacing: normal;
  word-break: normal;
  word-spacing: normal;
  white-space: normal;
  line-break: auto;
  font-size: 0.76562rem;
  word-wrap: break-word;
  opacity: 0; }
  .tooltip.show {
    opacity: 0.9; }
  .tooltip .arrow {
    position: absolute;
    display: block;
    width: 0.8rem;
    height: 0.4rem; }
    .tooltip .arrow::before {
      position: absolute;
      content: "";
      border-color: transparent;
      border-style: solid; }

.bs-tooltip-top, .bs-tooltip-auto[x-placement^="top"] {
  padding: 0.4rem 0; }
  .bs-tooltip-top .arrow, .bs-tooltip-auto[x-placement^="top"] .arrow {
    bottom: 0; }
    .bs-tooltip-top .arrow::before, .bs-tooltip-auto[x-placement^="top"] .arrow::before {
      top: 0;
      border-width: 0.4rem 0.4rem 0;
      border-top-color: #FFFFFF; }

.bs-tooltip-right, .bs-tooltip-auto[x-placement^="right"] {
  padding: 0 0.4rem; }
  .bs-tooltip-right .arrow, .bs-tooltip-auto[x-placement^="right"] .arrow {
    left: 0;
    width: 0.4rem;
    height: 0.8rem; }
    .bs-tooltip-right .arrow::before, .bs-tooltip-auto[x-placement^="right"] .arrow::before {
      right: 0;
      border-width: 0.4rem 0.4rem 0.4rem 0;
      border-right-color: #FFFFFF; }

.bs-tooltip-bottom, .bs-tooltip-auto[x-placement^="bottom"] {
  padding: 0.4rem 0; }
  .bs-tooltip-bottom .arrow, .bs-tooltip-auto[x-placement^="bottom"] .arrow {
    top: 0; }
    .bs-tooltip-bottom .arrow::before, .bs-tooltip-auto[x-placement^="bottom"] .arrow::before {
      bottom: 0;
      border-width: 0 0.4rem 0.4rem;
      border-bottom-color: #FFFFFF; }

.bs-tooltip-left, .bs-tooltip-auto[x-placement^="left"] {
  padding: 0 0.4rem; }
  .bs-tooltip-left .arrow, .bs-tooltip-auto[x-placement^="left"] .arrow {
    right: 0;
    width: 0.4rem;
    height: 0.8rem; }
    .bs-tooltip-left .arrow::before, .bs-tooltip-auto[x-placement^="left"] .arrow::before {
      left: 0;
      border-width: 0.4rem 0 0.4rem 0.4rem;
      border-left-color: #FFFFFF; }

.tooltip-inner {
  max-width: 170px;
  padding: 0.25rem 1rem;
  color: #fff;
  text-align: center;
  background-color: #FFFFFF;
  border-radius: 0.25rem; }

.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: block;
  max-width: 240px;
  font-family: Montserrat;
  font-style: normal;
  font-weight: 400;
  line-height: 1.6;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  letter-spacing: normal;
  word-break: normal;
  word-spacing: normal;
  white-space: normal;
  line-break: auto;
  font-size: 0.76562rem;
  word-wrap: break-word;
  background-color: #f96332;
  background-clip: padding-box;
  border: 0px solid rgba(0, 0, 0, 0.2);
  border-radius: 0.3rem; }
  .popover .arrow {
    position: absolute;
    display: block;
    width: 1rem;
    height: 0.5rem;
    margin: 0 0.3rem; }
    .popover .arrow::before, .popover .arrow::after {
      position: absolute;
      display: block;
      content: "";
      border-color: transparent;
      border-style: solid; }

.bs-popover-top, .bs-popover-auto[x-placement^="top"] {
  margin-bottom: 0.5rem; }
  .bs-popover-top .arrow, .bs-popover-auto[x-placement^="top"] .arrow {
    bottom: calc((0.5rem + 0px) * -1); }
  .bs-popover-top .arrow::before, .bs-popover-auto[x-placement^="top"] .arrow::before,
  .bs-popover-top .arrow::after, .bs-popover-auto[x-placement^="top"] .arrow::after {
    border-width: 0.5rem 0.5rem 0; }
  .bs-popover-top .arrow::before, .bs-popover-auto[x-placement^="top"] .arrow::before {
    bottom: 0;
    border-top-color: rgba(0, 0, 0, 0.25); }
  
  .bs-popover-top .arrow::after, .bs-popover-auto[x-placement^="top"] .arrow::after {
    bottom: 0px;
    border-top-color: #f96332; }

.bs-popover-right, .bs-popover-auto[x-placement^="right"] {
  margin-left: 0.5rem; }
  .bs-popover-right .arrow, .bs-popover-auto[x-placement^="right"] .arrow {
    left: calc((0.5rem + 0px) * -1);
    width: 0.5rem;
    height: 1rem;
    margin: 0.3rem 0; }
  .bs-popover-right .arrow::before, .bs-popover-auto[x-placement^="right"] .arrow::before,
  .bs-popover-right .arrow::after, .bs-popover-auto[x-placement^="right"] .arrow::after {
    border-width: 0.5rem 0.5rem 0.5rem 0; }
  .bs-popover-right .arrow::before, .bs-popover-auto[x-placement^="right"] .arrow::before {
    left: 0;
    border-right-color: rgba(0, 0, 0, 0.25); }
  
  .bs-popover-right .arrow::after, .bs-popover-auto[x-placement^="right"] .arrow::after {
    left: 0px;
    border-right-color: #f96332; }

.bs-popover-bottom, .bs-popover-auto[x-placement^="bottom"] {
  margin-top: 0.5rem; }
  .bs-popover-bottom .arrow, .bs-popover-auto[x-placement^="bottom"] .arrow {
    top: calc((0.5rem + 0px) * -1); }
  .bs-popover-bottom .arrow::before, .bs-popover-auto[x-placement^="bottom"] .arrow::before,
  .bs-popover-bottom .arrow::after, .bs-popover-auto[x-placement^="bottom"] .arrow::after {
    border-width: 0 0.5rem 0.5rem 0.5rem; }
  .bs-popover-bottom .arrow::before, .bs-popover-auto[x-placement^="bottom"] .arrow::before {
    top: 0;
    border-bottom-color: rgba(0, 0, 0, 0.25); }
  
  .bs-popover-bottom .arrow::after, .bs-popover-auto[x-placement^="bottom"] .arrow::after {
    top: 0px;
    border-bottom-color: #f96332; }
  .bs-popover-bottom .popover-header::before, .bs-popover-auto[x-placement^="bottom"] .popover-header::before {
    position: absolute;
    top: 0;
    left: 50%;
    display: block;
    width: 1rem;
    margin-left: -0.5rem;
    content: "";
    border-bottom: 0px solid #f96332; }

.bs-popover-left, .bs-popover-auto[x-placement^="left"] {
  margin-right: 0.5rem; }
  .bs-popover-left .arrow, .bs-popover-auto[x-placement^="left"] .arrow {
    right: calc((0.5rem + 0px) * -1);
    width: 0.5rem;
    height: 1rem;
    margin: 0.3rem 0; }
  .bs-popover-left .arrow::before, .bs-popover-auto[x-placement^="left"] .arrow::before,
  .bs-popover-left .arrow::after, .bs-popover-auto[x-placement^="left"] .arrow::after {
    border-width: 0.5rem 0 0.5rem 0.5rem; }
  .bs-popover-left .arrow::before, .bs-popover-auto[x-placement^="left"] .arrow::before {
    right: 0;
    border-left-color: rgba(0, 0, 0, 0.25); }
  
  .bs-popover-left .arrow::after, .bs-popover-auto[x-placement^="left"] .arrow::after {
    right: 0px;
    border-left-color: #f96332; }

.popover-header {
  padding: 0.5rem 0.75rem;
  margin-bottom: 0;
  font-size: 0.875rem;
  color: rgba(255, 255, 255, 0.6);
  background-color: #f96332;
  border-bottom: 0px solid #f85019;
  border-top-left-radius: calc(0.3rem - 0px);
  border-top-right-radius: calc(0.3rem - 0px); }
  .popover-header:empty {
    display: none; }

.popover-body {
  padding: 0.5rem 0.75rem;
  color: white; }

.carousel {
  position: relative; }

.carousel-inner {
  position: relative;
  width: 100%;
  overflow: hidden; }

.carousel-item {
  position: relative;
  display: none;
  align-items: center;
  width: 100%;
  transition: transform 0.6s ease;
  backface-visibility: hidden;
  perspective: 1000px; }

.carousel-item.active,
.carousel-item-next,
.carousel-item-prev {
  display: block; }

.carousel-item-next,
.carousel-item-prev {
  position: absolute;
  top: 0; }

.carousel-item-next.carousel-item-left,
.carousel-item-prev.carousel-item-right {
  transform: translateX(0); }
  @supports (transform-style: preserve-3d) {
    .carousel-item-next.carousel-item-left,
    .carousel-item-prev.carousel-item-right {
      transform: translate3d(0, 0, 0); } }

.carousel-item-next,
.active.carousel-item-right {
  transform: translateX(100%); }
  @supports (transform-style: preserve-3d) {
    .carousel-item-next,
    .active.carousel-item-right {
      transform: translate3d(100%, 0, 0); } }

.carousel-item-prev,
.active.carousel-item-left {
  transform: translateX(-100%); }
  @supports (transform-style: preserve-3d) {
    .carousel-item-prev,
    .active.carousel-item-left {
      transform: translate3d(-100%, 0, 0); } }

.carousel-control-prev,
.carousel-control-next {
  position: absolute;
  top: 0;
  bottom: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 15%;
  color: #fff;
  text-align: center;
  opacity: 0.5; }
  .carousel-control-prev:hover, .carousel-control-prev:focus,
  .carousel-control-next:hover,
  .carousel-control-next:focus {
    color: #fff;
    text-decoration: none;
    outline: 0;
    opacity: .9; }

.carousel-control-prev {
  left: 0; }

.carousel-control-next {
  right: 0; }

.carousel-control-prev-icon,
.carousel-control-next-icon {
  display: inline-block;
  width: 20px;
  height: 20px;
  background: transparent no-repeat center center;
  background-size: 100% 100%; }

.carousel-control-prev-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3E%3Cpath d='M5.25 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3E%3C/svg%3E"); }

.carousel-control-next-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3E%3Cpath d='M2.75 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3E%3C/svg%3E"); }

.carousel-indicators {
  position: absolute;
  right: 0;
  bottom: 10px;
  left: 0;
  z-index: 15;
  display: flex;
  justify-content: center;
  padding-left: 0;
  margin-right: 15%;
  margin-left: 15%;
  list-style: none; }
  .carousel-indicators li {
    position: relative;
    flex: 0 1 auto;
    width: 30px;
    height: 3px;
    margin-right: 3px;
    margin-left: 3px;
    text-indent: -999px;
    background-color: rgba(255, 255, 255, 0.5); }
    .carousel-indicators li::before {
      position: absolute;
      top: -10px;
      left: 0;
      display: inline-block;
      width: 100%;
      height: 10px;
      content: ""; }
    .carousel-indicators li::after {
      position: absolute;
      bottom: -10px;
      left: 0;
      display: inline-block;
      width: 100%;
      height: 10px;
      content: ""; }
  .carousel-indicators .active {
    background-color: #fff; }

.carousel-caption {
  position: absolute;
  right: 15%;
  bottom: 20px;
  left: 15%;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center; }

.align-baseline {
  vertical-align: baseline !important; }

.align-top {
  vertical-align: top !important; }

.align-middle {
  vertical-align: middle !important; }

.align-bottom {
  vertical-align: bottom !important; }

.align-text-bottom {
  vertical-align: text-bottom !important; }

.align-text-top {
  vertical-align: text-top !important; }

.bg-primary {
  background-color: #f96332 !important; }

a.bg-primary:hover, a.bg-primary:focus,
button.bg-primary:hover,
button.bg-primary:focus {
  background-color: #f14107 !important; }

.bg-secondary {
  background-color: #888 !important; }

a.bg-secondary:hover, a.bg-secondary:focus,
button.bg-secondary:hover,
button.bg-secondary:focus {
  background-color: #6f6f6f !important; }

.bg-success {
  background-color: #18ce0f !important; }

a.bg-success:hover, a.bg-success:focus,
button.bg-success:hover,
button.bg-success:focus {
  background-color: #129e0c !important; }

.bg-info {
  background-color: #2CA8FF !important; }

a.bg-info:hover, a.bg-info:focus,
button.bg-info:hover,
button.bg-info:focus {
  background-color: #0092f8 !important; }

.bg-warning {
  background-color: #FFB236 !important; }

a.bg-warning:hover, a.bg-warning:focus,
button.bg-warning:hover,
button.bg-warning:focus {
  background-color: #ff9e03 !important; }

.bg-danger {
  background-color: #FF3636 !important; }

a.bg-danger:hover, a.bg-danger:focus,
button.bg-danger:hover,
button.bg-danger:focus {
  background-color: #ff0303 !important; }

.bg-light {
  background-color: #FFFFFF !important; }

a.bg-light:hover, a.bg-light:focus,
button.bg-light:hover,
button.bg-light:focus {
  background-color: #e6e6e6 !important; }

.bg-dark {
  background-color: #2c2c2c !important; }

a.bg-dark:hover, a.bg-dark:focus,
button.bg-dark:hover,
button.bg-dark:focus {
  background-color: #131313 !important; }

.bg-gray {
  background-color: #EEEEEE !important; }

a.bg-gray:hover, a.bg-gray:focus,
button.bg-gray:hover,
button.bg-gray:focus {
  background-color: #d5d5d5 !important; }

.bg-white {
  background-color: #fff !important; }

.bg-transparent {
  background-color: transparent !important; }

.border {
  border: 1px solid #dee2e6 !important; }

.border-top {
  border-top: 1px solid #dee2e6 !important; }

.border-right {
  border-right: 1px solid #dee2e6 !important; }

.border-bottom {
  border-bottom: 1px solid #dee2e6 !important; }

.border-left {
  border-left: 1px solid #dee2e6 !important; }

.border-0 {
  border: 0 !important; }

.border-top-0 {
  border-top: 0 !important; }

.border-right-0 {
  border-right: 0 !important; }

.border-bottom-0 {
  border-bottom: 0 !important; }

.border-left-0 {
  border-left: 0 !important; }

.border-primary {
  border-color: #f96332 !important; }

.border-secondary {
  border-color: #888 !important; }

.border-success {
  border-color: #18ce0f !important; }

.border-info {
  border-color: #2CA8FF !important; }

.border-warning {
  border-color: #FFB236 !important; }

.border-danger {
  border-color: #FF3636 !important; }

.border-light {
  border-color: #FFFFFF !important; }

.border-dark {
  border-color: #2c2c2c !important; }

.border-gray {
  border-color: #EEEEEE !important; }

.border-white {
  border-color: #fff !important; }

.rounded {
  border-radius: 0.25rem !important; }

.rounded-top {
  border-top-left-radius: 0.25rem !important;
  border-top-right-radius: 0.25rem !important; }

.rounded-right {
  border-top-right-radius: 0.25rem !important;
  border-bottom-right-radius: 0.25rem !important; }

.rounded-bottom {
  border-bottom-right-radius: 0.25rem !important;
  border-bottom-left-radius: 0.25rem !important; }

.rounded-left {
  border-top-left-radius: 0.25rem !important;
  border-bottom-left-radius: 0.25rem !important; }

.rounded-circle {
  border-radius: 50% !important; }

.rounded-0 {
  border-radius: 0 !important; }

.clearfix::after {
  display: block;
  clear: both;
  content: ""; }

.d-none {
  display: none !important; }

.d-inline {
  display: inline !important; }

.d-inline-block {
  display: inline-block !important; }

.d-block {
  display: block !important; }

.d-table {
  display: table !important; }

.d-table-row {
  display: table-row !important; }

.d-table-cell {
  display: table-cell !important; }

.d-flex {
  display: flex !important; }

.d-inline-flex {
  display: inline-flex !important; }

@media (min-width: 576px) {
  .d-sm-none {
    display: none !important; }
  .d-sm-inline {
    display: inline !important; }
  .d-sm-inline-block {
    display: inline-block !important; }
  .d-sm-block {
    display: block !important; }
  .d-sm-table {
    display: table !important; }
  .d-sm-table-row {
    display: table-row !important; }
  .d-sm-table-cell {
    display: table-cell !important; }
  .d-sm-flex {
    display: flex !important; }
  .d-sm-inline-flex {
    display: inline-flex !important; } }

@media (min-width: 768px) {
  .d-md-none {
    display: none !important; }
  .d-md-inline {
    display: inline !important; }
  .d-md-inline-block {
    display: inline-block !important; }
  .d-md-block {
    display: block !important; }
  .d-md-table {
    display: table !important; }
  .d-md-table-row {
    display: table-row !important; }
  .d-md-table-cell {
    display: table-cell !important; }
  .d-md-flex {
    display: flex !important; }
  .d-md-inline-flex {
    display: inline-flex !important; } }

@media (min-width: 992px) {
  .d-lg-none {
    display: none !important; }
  .d-lg-inline {
    display: inline !important; }
  .d-lg-inline-block {
    display: inline-block !important; }
  .d-lg-block {
    display: block !important; }
  .d-lg-table {
    display: table !important; }
  .d-lg-table-row {
    display: table-row !important; }
  .d-lg-table-cell {
    display: table-cell !important; }
  .d-lg-flex {
    display: flex !important; }
  .d-lg-inline-flex {
    display: inline-flex !important; } }

@media (min-width: 1200px) {
  .d-xl-none {
    display: none !important; }
  .d-xl-inline {
    display: inline !important; }
  .d-xl-inline-block {
    display: inline-block !important; }
  .d-xl-block {
    display: block !important; }
  .d-xl-table {
    display: table !important; }
  .d-xl-table-row {
    display: table-row !important; }
  .d-xl-table-cell {
    display: table-cell !important; }
  .d-xl-flex {
    display: flex !important; }
  .d-xl-inline-flex {
    display: inline-flex !important; } }

@media print {
  .d-print-none {
    display: none !important; }
  .d-print-inline {
    display: inline !important; }
  .d-print-inline-block {
    display: inline-block !important; }
  .d-print-block {
    display: block !important; }
  .d-print-table {
    display: table !important; }
  .d-print-table-row {
    display: table-row !important; }
  .d-print-table-cell {
    display: table-cell !important; }
  .d-print-flex {
    display: flex !important; }
  .d-print-inline-flex {
    display: inline-flex !important; } }

.embed-responsive {
  position: relative;
  display: block;
  width: 100%;
  padding: 0;
  overflow: hidden; }
  .embed-responsive::before {
    display: block;
    content: ""; }
  .embed-responsive .embed-responsive-item,
  .embed-responsive iframe,
  .embed-responsive embed,
  .embed-responsive object,
  .embed-responsive video {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0; }

.embed-responsive-21by9::before {
  padding-top: 42.85714%; }

.embed-responsive-16by9::before {
  padding-top: 56.25%; }

.embed-responsive-4by3::before {
  padding-top: 75%; }

.embed-responsive-1by1::before {
  padding-top: 100%; }

.flex-row {
  flex-direction: row !important; }

.flex-column {
  flex-direction: column !important; }

.flex-row-reverse {
  flex-direction: row-reverse !important; }

.flex-column-reverse {
  flex-direction: column-reverse !important; }

.flex-wrap {
  flex-wrap: wrap !important; }

.flex-nowrap {
  flex-wrap: nowrap !important; }

.flex-wrap-reverse {
  flex-wrap: wrap-reverse !important; }

.justify-content-start {
  justify-content: flex-start !important; }

.justify-content-end {
  justify-content: flex-end !important; }

.justify-content-center {
  justify-content: center !important; }

.justify-content-between {
  justify-content: space-between !important; }

.justify-content-around {
  justify-content: space-around !important; }

.align-items-start {
  align-items: flex-start !important; }

.align-items-end {
  align-items: flex-end !important; }

.align-items-center {
  align-items: center !important; }

.align-items-baseline {
  align-items: baseline !important; }

.align-items-stretch {
  align-items: stretch !important; }

.align-content-start {
  align-content: flex-start !important; }

.align-content-end {
  align-content: flex-end !important; }

.align-content-center {
  align-content: center !important; }

.align-content-between {
  align-content: space-between !important; }

.align-content-around {
  align-content: space-around !important; }

.align-content-stretch {
  align-content: stretch !important; }

.align-self-auto {
  align-self: auto !important; }

.align-self-start {
  align-self: flex-start !important; }

.align-self-end {
  align-self: flex-end !important; }

.align-self-center {
  align-self: center !important; }

.align-self-baseline {
  align-self: baseline !important; }

.align-self-stretch {
  align-self: stretch !important; }

@media (min-width: 576px) {
  .flex-sm-row {
    flex-direction: row !important; }
  .flex-sm-column {
    flex-direction: column !important; }
  .flex-sm-row-reverse {
    flex-direction: row-reverse !important; }
  .flex-sm-column-reverse {
    flex-direction: column-reverse !important; }
  .flex-sm-wrap {
    flex-wrap: wrap !important; }
  .flex-sm-nowrap {
    flex-wrap: nowrap !important; }
  .flex-sm-wrap-reverse {
    flex-wrap: wrap-reverse !important; }
  .justify-content-sm-start {
    justify-content: flex-start !important; }
  .justify-content-sm-end {
    justify-content: flex-end !important; }
  .justify-content-sm-center {
    justify-content: center !important; }
  .justify-content-sm-between {
    justify-content: space-between !important; }
  .justify-content-sm-around {
    justify-content: space-around !important; }
  .align-items-sm-start {
    align-items: flex-start !important; }
  .align-items-sm-end {
    align-items: flex-end !important; }
  .align-items-sm-center {
    align-items: center !important; }
  .align-items-sm-baseline {
    align-items: baseline !important; }
  .align-items-sm-stretch {
    align-items: stretch !important; }
  .align-content-sm-start {
    align-content: flex-start !important; }
  .align-content-sm-end {
    align-content: flex-end !important; }
  .align-content-sm-center {
    align-content: center !important; }
  .align-content-sm-between {
    align-content: space-between !important; }
  .align-content-sm-around {
    align-content: space-around !important; }
  .align-content-sm-stretch {
    align-content: stretch !important; }
  .align-self-sm-auto {
    align-self: auto !important; }
  .align-self-sm-start {
    align-self: flex-start !important; }
  .align-self-sm-end {
    align-self: flex-end !important; }
  .align-self-sm-center {
    align-self: center !important; }
  .align-self-sm-baseline {
    align-self: baseline !important; }
  .align-self-sm-stretch {
    align-self: stretch !important; } }

@media (min-width: 768px) {
  .flex-md-row {
    flex-direction: row !important; }
  .flex-md-column {
    flex-direction: column !important; }
  .flex-md-row-reverse {
    flex-direction: row-reverse !important; }
  .flex-md-column-reverse {
    flex-direction: column-reverse !important; }
  .flex-md-wrap {
    flex-wrap: wrap !important; }
  .flex-md-nowrap {
    flex-wrap: nowrap !important; }
  .flex-md-wrap-reverse {
    flex-wrap: wrap-reverse !important; }
  .justify-content-md-start {
    justify-content: flex-start !important; }
  .justify-content-md-end {
    justify-content: flex-end !important; }
  .justify-content-md-center {
    justify-content: center !important; }
  .justify-content-md-between {
    justify-content: space-between !important; }
  .justify-content-md-around {
    justify-content: space-around !important; }
  .align-items-md-start {
    align-items: flex-start !important; }
  .align-items-md-end {
    align-items: flex-end !important; }
  .align-items-md-center {
    align-items: center !important; }
  .align-items-md-baseline {
    align-items: baseline !important; }
  .align-items-md-stretch {
    align-items: stretch !important; }
  .align-content-md-start {
    align-content: flex-start !important; }
  .align-content-md-end {
    align-content: flex-end !important; }
  .align-content-md-center {
    align-content: center !important; }
  .align-content-md-between {
    align-content: space-between !important; }
  .align-content-md-around {
    align-content: space-around !important; }
  .align-content-md-stretch {
    align-content: stretch !important; }
  .align-self-md-auto {
    align-self: auto !important; }
  .align-self-md-start {
    align-self: flex-start !important; }
  .align-self-md-end {
    align-self: flex-end !important; }
  .align-self-md-center {
    align-self: center !important; }
  .align-self-md-baseline {
    align-self: baseline !important; }
  .align-self-md-stretch {
    align-self: stretch !important; } }

@media (min-width: 992px) {
  .flex-lg-row {
    flex-direction: row !important; }
  .flex-lg-column {
    flex-direction: column !important; }
  .flex-lg-row-reverse {
    flex-direction: row-reverse !important; }
  .flex-lg-column-reverse {
    flex-direction: column-reverse !important; }
  .flex-lg-wrap {
    flex-wrap: wrap !important; }
  .flex-lg-nowrap {
    flex-wrap: nowrap !important; }
  .flex-lg-wrap-reverse {
    flex-wrap: wrap-reverse !important; }
  .justify-content-lg-start {
    justify-content: flex-start !important; }
  .justify-content-lg-end {
    justify-content: flex-end !important; }
  .justify-content-lg-center {
    justify-content: center !important; }
  .justify-content-lg-between {
    justify-content: space-between !important; }
  .justify-content-lg-around {
    justify-content: space-around !important; }
  .align-items-lg-start {
    align-items: flex-start !important; }
  .align-items-lg-end {
    align-items: flex-end !important; }
  .align-items-lg-center {
    align-items: center !important; }
  .align-items-lg-baseline {
    align-items: baseline !important; }
  .align-items-lg-stretch {
    align-items: stretch !important; }
  .align-content-lg-start {
    align-content: flex-start !important; }
  .align-content-lg-end {
    align-content: flex-end !important; }
  .align-content-lg-center {
    align-content: center !important; }
  .align-content-lg-between {
    align-content: space-between !important; }
  .align-content-lg-around {
    align-content: space-around !important; }
  .align-content-lg-stretch {
    align-content: stretch !important; }
  .align-self-lg-auto {
    align-self: auto !important; }
  .align-self-lg-start {
    align-self: flex-start !important; }
  .align-self-lg-end {
    align-self: flex-end !important; }
  .align-self-lg-center {
    align-self: center !important; }
  .align-self-lg-baseline {
    align-self: baseline !important; }
  .align-self-lg-stretch {
    align-self: stretch !important; } }

@media (min-width: 1200px) {
  .flex-xl-row {
    flex-direction: row !important; }
  .flex-xl-column {
    flex-direction: column !important; }
  .flex-xl-row-reverse {
    flex-direction: row-reverse !important; }
  .flex-xl-column-reverse {
    flex-direction: column-reverse !important; }
  .flex-xl-wrap {
    flex-wrap: wrap !important; }
  .flex-xl-nowrap {
    flex-wrap: nowrap !important; }
  .flex-xl-wrap-reverse {
    flex-wrap: wrap-reverse !important; }
  .justify-content-xl-start {
    justify-content: flex-start !important; }
  .justify-content-xl-end {
    justify-content: flex-end !important; }
  .justify-content-xl-center {
    justify-content: center !important; }
  .justify-content-xl-between {
    justify-content: space-between !important; }
  .justify-content-xl-around {
    justify-content: space-around !important; }
  .align-items-xl-start {
    align-items: flex-start !important; }
  .align-items-xl-end {
    align-items: flex-end !important; }
  .align-items-xl-center {
    align-items: center !important; }
  .align-items-xl-baseline {
    align-items: baseline !important; }
  .align-items-xl-stretch {
    align-items: stretch !important; }
  .align-content-xl-start {
    align-content: flex-start !important; }
  .align-content-xl-end {
    align-content: flex-end !important; }
  .align-content-xl-center {
    align-content: center !important; }
  .align-content-xl-between {
    align-content: space-between !important; }
  .align-content-xl-around {
    align-content: space-around !important; }
  .align-content-xl-stretch {
    align-content: stretch !important; }
  .align-self-xl-auto {
    align-self: auto !important; }
  .align-self-xl-start {
    align-self: flex-start !important; }
  .align-self-xl-end {
    align-self: flex-end !important; }
  .align-self-xl-center {
    align-self: center !important; }
  .align-self-xl-baseline {
    align-self: baseline !important; }
  .align-self-xl-stretch {
    align-self: stretch !important; } }

.float-left {
  float: left !important; }

.float-right {
  float: right !important; }

.float-none {
  float: none !important; }

@media (min-width: 576px) {
  .float-sm-left {
    float: left !important; }
  .float-sm-right {
    float: right !important; }
  .float-sm-none {
    float: none !important; } }

@media (min-width: 768px) {
  .float-md-left {
    float: left !important; }
  .float-md-right {
    float: right !important; }
  .float-md-none {
    float: none !important; } }

@media (min-width: 992px) {
  .float-lg-left {
    float: left !important; }
  .float-lg-right {
    float: right !important; }
  .float-lg-none {
    float: none !important; } }

@media (min-width: 1200px) {
  .float-xl-left {
    float: left !important; }
  .float-xl-right {
    float: right !important; }
  .float-xl-none {
    float: none !important; } }

.position-static {
  position: static !important; }

.position-relative {
  position: relative !important; }

.position-absolute {
  position: absolute !important; }

.position-fixed {
  position: fixed !important; }

.position-sticky {
  position: sticky !important; }

.fixed-top {
  position: fixed;
  top: 0;
  right: 0;
  left: 0;
  z-index: 1030; }

.fixed-bottom {
  position: fixed;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1030; }

@supports (position: sticky) {
  .sticky-top {
    position: sticky;
    top: 0;
    z-index: 1020; } }

.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  clip-path: inset(50%);
  border: 0; }

.sr-only-focusable:active, .sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  overflow: visible;
  clip: auto;
  white-space: normal;
  clip-path: none; }

.w-25 {
  width: 25% !important; }

.w-50 {
  width: 50% !important; }

.w-75 {
  width: 75% !important; }

.w-100 {
  width: 100% !important; }

.h-25 {
  height: 25% !important; }

.h-50 {
  height: 50% !important; }

.h-75 {
  height: 75% !important; }

.h-100 {
  height: 100% !important; }

.mw-100 {
  max-width: 100% !important; }

.mh-100 {
  max-height: 100% !important; }

.m-0 {
  margin: 0 !important; }

.mt-0,
.my-0 {
  margin-top: 0 !important; }

.mr-0,
.mx-0 {
  margin-right: 0 !important; }

.mb-0,
.my-0 {
  margin-bottom: 0 !important; }

.ml-0,
.mx-0 {
  margin-left: 0 !important; }

.m-1 {
  margin: 0.25rem !important; }

.mt-1,
.my-1 {
  margin-top: 0.25rem !important; }

.mr-1,
.mx-1 {
  margin-right: 0.25rem !important; }

.mb-1,
.my-1 {
  margin-bottom: 0.25rem !important; }

.ml-1,
.mx-1 {
  margin-left: 0.25rem !important; }

.m-2 {
  margin: 0.5rem !important; }

.mt-2,
.my-2 {
  margin-top: 0.5rem !important; }

.mr-2,
.mx-2 {
  margin-right: 0.5rem !important; }

.mb-2,
.my-2 {
  margin-bottom: 0.5rem !important; }

.ml-2,
.mx-2 {
  margin-left: 0.5rem !important; }

.m-3 {
  margin: 1rem !important; }

.mt-3,
.my-3 {
  margin-top: 1rem !important; }

.mr-3,
.mx-3 {
  margin-right: 1rem !important; }

.mb-3,
.my-3 {
  margin-bottom: 1rem !important; }

.ml-3,
.mx-3 {
  margin-left: 1rem !important; }

.m-4 {
  margin: 1.5rem !important; }

.mt-4,
.my-4 {
  margin-top: 1.5rem !important; }

.mr-4,
.mx-4 {
  margin-right: 1.5rem !important; }

.mb-4,
.my-4 {
  margin-bottom: 1.5rem !important; }

.ml-4,
.mx-4 {
  margin-left: 1.5rem !important; }

.m-5 {
  margin: 3rem !important; }

.mt-5,
.my-5 {
  margin-top: 3rem !important; }

.mr-5,
.mx-5 {
  margin-right: 3rem !important; }

.mb-5,
.my-5 {
  margin-bottom: 3rem !important; }

.ml-5,
.mx-5 {
  margin-left: 3rem !important; }

.p-0 {
  padding: 0 !important; }

.pt-0,
.py-0 {
  padding-top: 0 !important; }

.pr-0,
.px-0 {
  padding-right: 0 !important; }

.pb-0,
.py-0 {
  padding-bottom: 0 !important; }

.pl-0,
.px-0 {
  padding-left: 0 !important; }

.p-1 {
  padding: 0.25rem !important; }

.pt-1,
.py-1 {
  padding-top: 0.25rem !important; }

.pr-1,
.px-1 {
  padding-right: 0.25rem !important; }

.pb-1,
.py-1 {
  padding-bottom: 0.25rem !important; }

.pl-1,
.px-1 {
  padding-left: 0.25rem !important; }

.p-2 {
  padding: 0.5rem !important; }

.pt-2,
.py-2 {
  padding-top: 0.5rem !important; }

.pr-2,
.px-2 {
  padding-right: 0.5rem !important; }

.pb-2,
.py-2 {
  padding-bottom: 0.5rem !important; }

.pl-2,
.px-2 {
  padding-left: 0.5rem !important; }

.p-3 {
  padding: 1rem !important; }

.pt-3,
.py-3 {
  padding-top: 1rem !important; }

.pr-3,
.px-3 {
  padding-right: 1rem !important; }

.pb-3,
.py-3 {
  padding-bottom: 1rem !important; }

.pl-3,
.px-3 {
  padding-left: 1rem !important; }

.p-4 {
  padding: 1.5rem !important; }

.pt-4,
.py-4 {
  padding-top: 1.5rem !important; }

.pr-4,
.px-4 {
  padding-right: 1.5rem !important; }

.pb-4,
.py-4 {
  padding-bottom: 1.5rem !important; }

.pl-4,
.px-4 {
  padding-left: 1.5rem !important; }

.p-5 {
  padding: 3rem !important; }

.pt-5,
.py-5 {
  padding-top: 3rem !important; }

.pr-5,
.px-5 {
  padding-right: 3rem !important; }

.pb-5,
.py-5 {
  padding-bottom: 3rem !important; }

.pl-5,
.px-5 {
  padding-left: 3rem !important; }

.m-auto {
  margin: auto !important; }

.mt-auto,
.my-auto {
  margin-top: auto !important; }

.mr-auto,
.mx-auto {
  margin-right: auto !important; }

.mb-auto,
.my-auto {
  margin-bottom: auto !important; }

.ml-auto,
.mx-auto {
  margin-left: auto !important; }

@media (min-width: 576px) {
  .m-sm-0 {
    margin: 0 !important; }
  .mt-sm-0,
  .my-sm-0 {
    margin-top: 0 !important; }
  .mr-sm-0,
  .mx-sm-0 {
    margin-right: 0 !important; }
  .mb-sm-0,
  .my-sm-0 {
    margin-bottom: 0 !important; }
  .ml-sm-0,
  .mx-sm-0 {
    margin-left: 0 !important; }
  .m-sm-1 {
    margin: 0.25rem !important; }
  .mt-sm-1,
  .my-sm-1 {
    margin-top: 0.25rem !important; }
  .mr-sm-1,
  .mx-sm-1 {
    margin-right: 0.25rem !important; }
  .mb-sm-1,
  .my-sm-1 {
    margin-bottom: 0.25rem !important; }
  .ml-sm-1,
  .mx-sm-1 {
    margin-left: 0.25rem !important; }
  .m-sm-2 {
    margin: 0.5rem !important; }
  .mt-sm-2,
  .my-sm-2 {
    margin-top: 0.5rem !important; }
  .mr-sm-2,
  .mx-sm-2 {
    margin-right: 0.5rem !important; }
  .mb-sm-2,
  .my-sm-2 {
    margin-bottom: 0.5rem !important; }
  .ml-sm-2,
  .mx-sm-2 {
    margin-left: 0.5rem !important; }
  .m-sm-3 {
    margin: 1rem !important; }
  .mt-sm-3,
  .my-sm-3 {
    margin-top: 1rem !important; }
  .mr-sm-3,
  .mx-sm-3 {
    margin-right: 1rem !important; }
  .mb-sm-3,
  .my-sm-3 {
    margin-bottom: 1rem !important; }
  .ml-sm-3,
  .mx-sm-3 {
    margin-left: 1rem !important; }
  .m-sm-4 {
    margin: 1.5rem !important; }
  .mt-sm-4,
  .my-sm-4 {
    margin-top: 1.5rem !important; }
  .mr-sm-4,
  .mx-sm-4 {
    margin-right: 1.5rem !important; }
  .mb-sm-4,
  .my-sm-4 {
    margin-bottom: 1.5rem !important; }
  .ml-sm-4,
  .mx-sm-4 {
    margin-left: 1.5rem !important; }
  .m-sm-5 {
    margin: 3rem !important; }
  .mt-sm-5,
  .my-sm-5 {
    margin-top: 3rem !important; }
  .mr-sm-5,
  .mx-sm-5 {
    margin-right: 3rem !important; }
  .mb-sm-5,
  .my-sm-5 {
    margin-bottom: 3rem !important; }
  .ml-sm-5,
  .mx-sm-5 {
    margin-left: 3rem !important; }
  .p-sm-0 {
    padding: 0 !important; }
  .pt-sm-0,
  .py-sm-0 {
    padding-top: 0 !important; }
  .pr-sm-0,
  .px-sm-0 {
    padding-right: 0 !important; }
  .pb-sm-0,
  .py-sm-0 {
    padding-bottom: 0 !important; }
  .pl-sm-0,
  .px-sm-0 {
    padding-left: 0 !important; }
  .p-sm-1 {
    padding: 0.25rem !important; }
  .pt-sm-1,
  .py-sm-1 {
    padding-top: 0.25rem !important; }
  .pr-sm-1,
  .px-sm-1 {
    padding-right: 0.25rem !important; }
  .pb-sm-1,
  .py-sm-1 {
    padding-bottom: 0.25rem !important; }
  .pl-sm-1,
  .px-sm-1 {
    padding-left: 0.25rem !important; }
  .p-sm-2 {
    padding: 0.5rem !important; }
  .pt-sm-2,
  .py-sm-2 {
    padding-top: 0.5rem !important; }
  .pr-sm-2,
  .px-sm-2 {
    padding-right: 0.5rem !important; }
  .pb-sm-2,
  .py-sm-2 {
    padding-bottom: 0.5rem !important; }
  .pl-sm-2,
  .px-sm-2 {
    padding-left: 0.5rem !important; }
  .p-sm-3 {
    padding: 1rem !important; }
  .pt-sm-3,
  .py-sm-3 {
    padding-top: 1rem !important; }
  .pr-sm-3,
  .px-sm-3 {
    padding-right: 1rem !important; }
  .pb-sm-3,
  .py-sm-3 {
    padding-bottom: 1rem !important; }
  .pl-sm-3,
  .px-sm-3 {
    padding-left: 1rem !important; }
  .p-sm-4 {
    padding: 1.5rem !important; }
  .pt-sm-4,
  .py-sm-4 {
    padding-top: 1.5rem !important; }
  .pr-sm-4,
  .px-sm-4 {
    padding-right: 1.5rem !important; }
  .pb-sm-4,
  .py-sm-4 {
    padding-bottom: 1.5rem !important; }
  .pl-sm-4,
  .px-sm-4 {
    padding-left: 1.5rem !important; }
  .p-sm-5 {
    padding: 3rem !important; }
  .pt-sm-5,
  .py-sm-5 {
    padding-top: 3rem !important; }
  .pr-sm-5,
  .px-sm-5 {
    padding-right: 3rem !important; }
  .pb-sm-5,
  .py-sm-5 {
    padding-bottom: 3rem !important; }
  .pl-sm-5,
  .px-sm-5 {
    padding-left: 3rem !important; }
  .m-sm-auto {
    margin: auto !important; }
  .mt-sm-auto,
  .my-sm-auto {
    margin-top: auto !important; }
  .mr-sm-auto,
  .mx-sm-auto {
    margin-right: auto !important; }
  .mb-sm-auto,
  .my-sm-auto {
    margin-bottom: auto !important; }
  .ml-sm-auto,
  .mx-sm-auto {
    margin-left: auto !important; } }

@media (min-width: 768px) {
  .m-md-0 {
    margin: 0 !important; }
  .mt-md-0,
  .my-md-0 {
    margin-top: 0 !important; }
  .mr-md-0,
  .mx-md-0 {
    margin-right: 0 !important; }
  .mb-md-0,
  .my-md-0 {
    margin-bottom: 0 !important; }
  .ml-md-0,
  .mx-md-0 {
    margin-left: 0 !important; }
  .m-md-1 {
    margin: 0.25rem !important; }
  .mt-md-1,
  .my-md-1 {
    margin-top: 0.25rem !important; }
  .mr-md-1,
  .mx-md-1 {
    margin-right: 0.25rem !important; }
  .mb-md-1,
  .my-md-1 {
    margin-bottom: 0.25rem !important; }
  .ml-md-1,
  .mx-md-1 {
    margin-left: 0.25rem !important; }
  .m-md-2 {
    margin: 0.5rem !important; }
  .mt-md-2,
  .my-md-2 {
    margin-top: 0.5rem !important; }
  .mr-md-2,
  .mx-md-2 {
    margin-right: 0.5rem !important; }
  .mb-md-2,
  .my-md-2 {
    margin-bottom: 0.5rem !important; }
  .ml-md-2,
  .mx-md-2 {
    margin-left: 0.5rem !important; }
  .m-md-3 {
    margin: 1rem !important; }
  .mt-md-3,
  .my-md-3 {
    margin-top: 1rem !important; }
  .mr-md-3,
  .mx-md-3 {
    margin-right: 1rem !important; }
  .mb-md-3,
  .my-md-3 {
    margin-bottom: 1rem !important; }
  .ml-md-3,
  .mx-md-3 {
    margin-left: 1rem !important; }
  .m-md-4 {
    margin: 1.5rem !important; }
  .mt-md-4,
  .my-md-4 {
    margin-top: 1.5rem !important; }
  .mr-md-4,
  .mx-md-4 {
    margin-right: 1.5rem !important; }
  .mb-md-4,
  .my-md-4 {
    margin-bottom: 1.5rem !important; }
  .ml-md-4,
  .mx-md-4 {
    margin-left: 1.5rem !important; }
  .m-md-5 {
    margin: 3rem !important; }
  .mt-md-5,
  .my-md-5 {
    margin-top: 3rem !important; }
  .mr-md-5,
  .mx-md-5 {
    margin-right: 3rem !important; }
  .mb-md-5,
  .my-md-5 {
    margin-bottom: 3rem !important; }
  .ml-md-5,
  .mx-md-5 {
    margin-left: 3rem !important; }
  .p-md-0 {
    padding: 0 !important; }
  .pt-md-0,
  .py-md-0 {
    padding-top: 0 !important; }
  .pr-md-0,
  .px-md-0 {
    padding-right: 0 !important; }
  .pb-md-0,
  .py-md-0 {
    padding-bottom: 0 !important; }
  .pl-md-0,
  .px-md-0 {
    padding-left: 0 !important; }
  .p-md-1 {
    padding: 0.25rem !important; }
  .pt-md-1,
  .py-md-1 {
    padding-top: 0.25rem !important; }
  .pr-md-1,
  .px-md-1 {
    padding-right: 0.25rem !important; }
  .pb-md-1,
  .py-md-1 {
    padding-bottom: 0.25rem !important; }
  .pl-md-1,
  .px-md-1 {
    padding-left: 0.25rem !important; }
  .p-md-2 {
    padding: 0.5rem !important; }
  .pt-md-2,
  .py-md-2 {
    padding-top: 0.5rem !important; }
  .pr-md-2,
  .px-md-2 {
    padding-right: 0.5rem !important; }
  .pb-md-2,
  .py-md-2 {
    padding-bottom: 0.5rem !important; }
  .pl-md-2,
  .px-md-2 {
    padding-left: 0.5rem !important; }
  .p-md-3 {
    padding: 1rem !important; }
  .pt-md-3,
  .py-md-3 {
    padding-top: 1rem !important; }
  .pr-md-3,
  .px-md-3 {
    padding-right: 1rem !important; }
  .pb-md-3,
  .py-md-3 {
    padding-bottom: 1rem !important; }
  .pl-md-3,
  .px-md-3 {
    padding-left: 1rem !important; }
  .p-md-4 {
    padding: 1.5rem !important; }
  .pt-md-4,
  .py-md-4 {
    padding-top: 1.5rem !important; }
  .pr-md-4,
  .px-md-4 {
    padding-right: 1.5rem !important; }
  .pb-md-4,
  .py-md-4 {
    padding-bottom: 1.5rem !important; }
  .pl-md-4,
  .px-md-4 {
    padding-left: 1.5rem !important; }
  .p-md-5 {
    padding: 3rem !important; }
  .pt-md-5,
  .py-md-5 {
    padding-top: 3rem !important; }
  .pr-md-5,
  .px-md-5 {
    padding-right: 3rem !important; }
  .pb-md-5,
  .py-md-5 {
    padding-bottom: 3rem !important; }
  .pl-md-5,
  .px-md-5 {
    padding-left: 3rem !important; }
  .m-md-auto {
    margin: auto !important; }
  .mt-md-auto,
  .my-md-auto {
    margin-top: auto !important; }
  .mr-md-auto,
  .mx-md-auto {
    margin-right: auto !important; }
  .mb-md-auto,
  .my-md-auto {
    margin-bottom: auto !important; }
  .ml-md-auto,
  .mx-md-auto {
    margin-left: auto !important; } }

@media (min-width: 992px) {
  .m-lg-0 {
    margin: 0 !important; }
  .mt-lg-0,
  .my-lg-0 {
    margin-top: 0 !important; }
  .mr-lg-0,
  .mx-lg-0 {
    margin-right: 0 !important; }
  .mb-lg-0,
  .my-lg-0 {
    margin-bottom: 0 !important; }
  .ml-lg-0,
  .mx-lg-0 {
    margin-left: 0 !important; }
  .m-lg-1 {
    margin: 0.25rem !important; }
  .mt-lg-1,
  .my-lg-1 {
    margin-top: 0.25rem !important; }
  .mr-lg-1,
  .mx-lg-1 {
    margin-right: 0.25rem !important; }
  .mb-lg-1,
  .my-lg-1 {
    margin-bottom: 0.25rem !important; }
  .ml-lg-1,
  .mx-lg-1 {
    margin-left: 0.25rem !important; }
  .m-lg-2 {
    margin: 0.5rem !important; }
  .mt-lg-2,
  .my-lg-2 {
    margin-top: 0.5rem !important; }
  .mr-lg-2,
  .mx-lg-2 {
    margin-right: 0.5rem !important; }
  .mb-lg-2,
  .my-lg-2 {
    margin-bottom: 0.5rem !important; }
  .ml-lg-2,
  .mx-lg-2 {
    margin-left: 0.5rem !important; }
  .m-lg-3 {
    margin: 1rem !important; }
  .mt-lg-3,
  .my-lg-3 {
    margin-top: 1rem !important; }
  .mr-lg-3,
  .mx-lg-3 {
    margin-right: 1rem !important; }
  .mb-lg-3,
  .my-lg-3 {
    margin-bottom: 1rem !important; }
  .ml-lg-3,
  .mx-lg-3 {
    margin-left: 1rem !important; }
  .m-lg-4 {
    margin: 1.5rem !important; }
  .mt-lg-4,
  .my-lg-4 {
    margin-top: 1.5rem !important; }
  .mr-lg-4,
  .mx-lg-4 {
    margin-right: 1.5rem !important; }
  .mb-lg-4,
  .my-lg-4 {
    margin-bottom: 1.5rem !important; }
  .ml-lg-4,
  .mx-lg-4 {
    margin-left: 1.5rem !important; }
  .m-lg-5 {
    margin: 3rem !important; }
  .mt-lg-5,
  .my-lg-5 {
    margin-top: 3rem !important; }
  .mr-lg-5,
  .mx-lg-5 {
    margin-right: 3rem !important; }
  .mb-lg-5,
  .my-lg-5 {
    margin-bottom: 3rem !important; }
  .ml-lg-5,
  .mx-lg-5 {
    margin-left: 3rem !important; }
  .p-lg-0 {
    padding: 0 !important; }
  .pt-lg-0,
  .py-lg-0 {
    padding-top: 0 !important; }
  .pr-lg-0,
  .px-lg-0 {
    padding-right: 0 !important; }
  .pb-lg-0,
  .py-lg-0 {
    padding-bottom: 0 !important; }
  .pl-lg-0,
  .px-lg-0 {
    padding-left: 0 !important; }
  .p-lg-1 {
    padding: 0.25rem !important; }
  .pt-lg-1,
  .py-lg-1 {
    padding-top: 0.25rem !important; }
  .pr-lg-1,
  .px-lg-1 {
    padding-right: 0.25rem !important; }
  .pb-lg-1,
  .py-lg-1 {
    padding-bottom: 0.25rem !important; }
  .pl-lg-1,
  .px-lg-1 {
    padding-left: 0.25rem !important; }
  .p-lg-2 {
    padding: 0.5rem !important; }
  .pt-lg-2,
  .py-lg-2 {
    padding-top: 0.5rem !important; }
  .pr-lg-2,
  .px-lg-2 {
    padding-right: 0.5rem !important; }
  .pb-lg-2,
  .py-lg-2 {
    padding-bottom: 0.5rem !important; }
  .pl-lg-2,
  .px-lg-2 {
    padding-left: 0.5rem !important; }
  .p-lg-3 {
    padding: 1rem !important; }
  .pt-lg-3,
  .py-lg-3 {
    padding-top: 1rem !important; }
  .pr-lg-3,
  .px-lg-3 {
    padding-right: 1rem !important; }
  .pb-lg-3,
  .py-lg-3 {
    padding-bottom: 1rem !important; }
  .pl-lg-3,
  .px-lg-3 {
    padding-left: 1rem !important; }
  .p-lg-4 {
    padding: 1.5rem !important; }
  .pt-lg-4,
  .py-lg-4 {
    padding-top: 1.5rem !important; }
  .pr-lg-4,
  .px-lg-4 {
    padding-right: 1.5rem !important; }
  .pb-lg-4,
  .py-lg-4 {
    padding-bottom: 1.5rem !important; }
  .pl-lg-4,
  .px-lg-4 {
    padding-left: 1.5rem !important; }
  .p-lg-5 {
    padding: 3rem !important; }
  .pt-lg-5,
  .py-lg-5 {
    padding-top: 3rem !important; }
  .pr-lg-5,
  .px-lg-5 {
    padding-right: 3rem !important; }
  .pb-lg-5,
  .py-lg-5 {
    padding-bottom: 3rem !important; }
  .pl-lg-5,
  .px-lg-5 {
    padding-left: 3rem !important; }
  .m-lg-auto {
    margin: auto !important; }
  .mt-lg-auto,
  .my-lg-auto {
    margin-top: auto !important; }
  .mr-lg-auto,
  .mx-lg-auto {
    margin-right: auto !important; }
  .mb-lg-auto,
  .my-lg-auto {
    margin-bottom: auto !important; }
  .ml-lg-auto,
  .mx-lg-auto {
    margin-left: auto !important; } }

@media (min-width: 1200px) {
  .m-xl-0 {
    margin: 0 !important; }
  .mt-xl-0,
  .my-xl-0 {
    margin-top: 0 !important; }
  .mr-xl-0,
  .mx-xl-0 {
    margin-right: 0 !important; }
  .mb-xl-0,
  .my-xl-0 {
    margin-bottom: 0 !important; }
  .ml-xl-0,
  .mx-xl-0 {
    margin-left: 0 !important; }
  .m-xl-1 {
    margin: 0.25rem !important; }
  .mt-xl-1,
  .my-xl-1 {
    margin-top: 0.25rem !important; }
  .mr-xl-1,
  .mx-xl-1 {
    margin-right: 0.25rem !important; }
  .mb-xl-1,
  .my-xl-1 {
    margin-bottom: 0.25rem !important; }
  .ml-xl-1,
  .mx-xl-1 {
    margin-left: 0.25rem !important; }
  .m-xl-2 {
    margin: 0.5rem !important; }
  .mt-xl-2,
  .my-xl-2 {
    margin-top: 0.5rem !important; }
  .mr-xl-2,
  .mx-xl-2 {
    margin-right: 0.5rem !important; }
  .mb-xl-2,
  .my-xl-2 {
    margin-bottom: 0.5rem !important; }
  .ml-xl-2,
  .mx-xl-2 {
    margin-left: 0.5rem !important; }
  .m-xl-3 {
    margin: 1rem !important; }
  .mt-xl-3,
  .my-xl-3 {
    margin-top: 1rem !important; }
  .mr-xl-3,
  .mx-xl-3 {
    margin-right: 1rem !important; }
  .mb-xl-3,
  .my-xl-3 {
    margin-bottom: 1rem !important; }
  .ml-xl-3,
  .mx-xl-3 {
    margin-left: 1rem !important; }
  .m-xl-4 {
    margin: 1.5rem !important; }
  .mt-xl-4,
  .my-xl-4 {
    margin-top: 1.5rem !important; }
  .mr-xl-4,
  .mx-xl-4 {
    margin-right: 1.5rem !important; }
  .mb-xl-4,
  .my-xl-4 {
    margin-bottom: 1.5rem !important; }
  .ml-xl-4,
  .mx-xl-4 {
    margin-left: 1.5rem !important; }
  .m-xl-5 {
    margin: 3rem !important; }
  .mt-xl-5,
  .my-xl-5 {
    margin-top: 3rem !important; }
  .mr-xl-5,
  .mx-xl-5 {
    margin-right: 3rem !important; }
  .mb-xl-5,
  .my-xl-5 {
    margin-bottom: 3rem !important; }
  .ml-xl-5,
  .mx-xl-5 {
    margin-left: 3rem !important; }
  .p-xl-0 {
    padding: 0 !important; }
  .pt-xl-0,
  .py-xl-0 {
    padding-top: 0 !important; }
  .pr-xl-0,
  .px-xl-0 {
    padding-right: 0 !important; }
  .pb-xl-0,
  .py-xl-0 {
    padding-bottom: 0 !important; }
  .pl-xl-0,
  .px-xl-0 {
    padding-left: 0 !important; }
  .p-xl-1 {
    padding: 0.25rem !important; }
  .pt-xl-1,
  .py-xl-1 {
    padding-top: 0.25rem !important; }
  .pr-xl-1,
  .px-xl-1 {
    padding-right: 0.25rem !important; }
  .pb-xl-1,
  .py-xl-1 {
    padding-bottom: 0.25rem !important; }
  .pl-xl-1,
  .px-xl-1 {
    padding-left: 0.25rem !important; }
  .p-xl-2 {
    padding: 0.5rem !important; }
  .pt-xl-2,
  .py-xl-2 {
    padding-top: 0.5rem !important; }
  .pr-xl-2,
  .px-xl-2 {
    padding-right: 0.5rem !important; }
  .pb-xl-2,
  .py-xl-2 {
    padding-bottom: 0.5rem !important; }
  .pl-xl-2,
  .px-xl-2 {
    padding-left: 0.5rem !important; }
  .p-xl-3 {
    padding: 1rem !important; }
  .pt-xl-3,
  .py-xl-3 {
    padding-top: 1rem !important; }
  .pr-xl-3,
  .px-xl-3 {
    padding-right: 1rem !important; }
  .pb-xl-3,
  .py-xl-3 {
    padding-bottom: 1rem !important; }
  .pl-xl-3,
  .px-xl-3 {
    padding-left: 1rem !important; }
  .p-xl-4 {
    padding: 1.5rem !important; }
  .pt-xl-4,
  .py-xl-4 {
    padding-top: 1.5rem !important; }
  .pr-xl-4,
  .px-xl-4 {
    padding-right: 1.5rem !important; }
  .pb-xl-4,
  .py-xl-4 {
    padding-bottom: 1.5rem !important; }
  .pl-xl-4,
  .px-xl-4 {
    padding-left: 1.5rem !important; }
  .p-xl-5 {
    padding: 3rem !important; }
  .pt-xl-5,
  .py-xl-5 {
    padding-top: 3rem !important; }
  .pr-xl-5,
  .px-xl-5 {
    padding-right: 3rem !important; }
  .pb-xl-5,
  .py-xl-5 {
    padding-bottom: 3rem !important; }
  .pl-xl-5,
  .px-xl-5 {
    padding-left: 3rem !important; }
  .m-xl-auto {
    margin: auto !important; }
  .mt-xl-auto,
  .my-xl-auto {
    margin-top: auto !important; }
  .mr-xl-auto,
  .mx-xl-auto {
    margin-right: auto !important; }
  .mb-xl-auto,
  .my-xl-auto {
    margin-bottom: auto !important; }
  .ml-xl-auto,
  .mx-xl-auto {
    margin-left: auto !important; } }

.text-justify {
  text-align: justify !important; }

.text-nowrap {
  white-space: nowrap !important; }

.text-truncate {
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap; }

.text-left {
  text-align: left !important; }

.text-right {
  text-align: right !important; }

.text-center {
  text-align: center !important; }

@media (min-width: 576px) {
  .text-sm-left {
    text-align: left !important; }
  .text-sm-right {
    text-align: right !important; }
  .text-sm-center {
    text-align: center !important; } }

@media (min-width: 768px) {
  .text-md-left {
    text-align: left !important; }
  .text-md-right {
    text-align: right !important; }
  .text-md-center {
    text-align: center !important; } }

@media (min-width: 992px) {
  .text-lg-left {
    text-align: left !important; }
  .text-lg-right {
    text-align: right !important; }
  .text-lg-center {
    text-align: center !important; } }

@media (min-width: 1200px) {
  .text-xl-left {
    text-align: left !important; }
  .text-xl-right {
    text-align: right !important; }
  .text-xl-center {
    text-align: center !important; } }

.text-lowercase {
  text-transform: lowercase !important; }

.text-uppercase {
  text-transform: uppercase !important; }

.text-capitalize {
  text-transform: capitalize !important; }

.font-weight-light {
  font-weight: 300 !important; }

.font-weight-normal {
  font-weight: 400 !important; }

.font-weight-bold {
  font-weight: 700 !important; }

.font-italic {
  font-style: italic !important; }

.text-white {
  color: #fff !important; }

.text-primary {
  color: #f96332 !important; }

a.text-primary:hover, a.text-primary:focus {
  color: #f14107 !important; }

.text-secondary {
  color: #888 !important; }

a.text-secondary:hover, a.text-secondary:focus {
  color: #6f6f6f !important; }

.text-success {
  color: #18ce0f !important; }

a.text-success:hover, a.text-success:focus {
  color: #129e0c !important; }

.text-info {
  color: #2CA8FF !important; }

a.text-info:hover, a.text-info:focus {
  color: #0092f8 !important; }

.text-warning {
  color: #FFB236 !important; }

a.text-warning:hover, a.text-warning:focus {
  color: #ff9e03 !important; }

.text-danger {
  color: #FF3636 !important; }

a.text-danger:hover, a.text-danger:focus {
  color: #ff0303 !important; }

.text-light {
  color: #FFFFFF !important; }

a.text-light:hover, a.text-light:focus {
  color: #e6e6e6 !important; }

.text-dark {
  color: #2c2c2c !important; }

a.text-dark:hover, a.text-dark:focus {
  color: #131313 !important; }

.text-gray {
  color: #EEEEEE !important; }

a.text-gray:hover, a.text-gray:focus {
  color: #d5d5d5 !important; }

.text-muted {
  color: #9A9A9A !important; }

.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0; }

.visible {
  visibility: visible !important; }

.invisible {
  visibility: hidden !important; }

@media print {
  *,
  *::before,
  *::after {
    text-shadow: none !important;
    box-shadow: none !important; }
  a:not(.btn) {
    text-decoration: underline; }
  abbr[title]::after {
    content: " (" attr(title) ")"; }
  pre {
    white-space: pre-wrap !important; }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid; }
  thead {
    display: table-header-group; }
  tr,
  img {
    page-break-inside: avoid; }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3; }
  h2,
  h3 {
    page-break-after: avoid; }
  @page {
    size: a3; }
  body {
    min-width: 992px !important; }
  .container {
    min-width: 992px !important; }
  .navbar {
    display: none; }
  .badge {
    border: 1px solid #000; }
  .table {
    border-collapse: collapse !important; }
    .table td,
    .table th {
      background-color: #fff !important; }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important; } }

.card {
  color: #888; }

.modal-content {
  color: #888; }

.list-group-item {
  color: #888; }

.bg-primary {
  color: #fff; }

.bg-secondary {
  color: #fff; }

.bg-success {
  color: #fff; }

.bg-info {
  color: #fff; }

.bg-warning {
  color: #fff; }

.bg-danger {
  color: #fff; }

.bg-light {
  color: #888; }

.bg-dark {
  color: #fff; }

.bg-gray {
  color: #888; }

.nav.nav-tabs {
  background-color: white; }
  .nav.nav-tabs .nav-link {
    color: #888; }
    .nav.nav-tabs .nav-link.active {
      border: 1px solid #888;
      border-radius: 30px; }
  .nav.nav-tabs.bg-primary > .nav-item > .nav-link {
    background-color: transparent;
    color: #fff; }
    .nav.nav-tabs.bg-primary > .nav-item > .nav-link.active {
      border: 1px solid #fff;
      border-radius: 30px; }
  .nav.nav-tabs.bg-secondary > .nav-item > .nav-link {
    background-color: transparent;
    color: #fff; }
    .nav.nav-tabs.bg-secondary > .nav-item > .nav-link.active {
      border: 1px solid #fff;
      border-radius: 30px; }
  .nav.nav-tabs.bg-success > .nav-item > .nav-link {
    background-color: transparent;
    color: #fff; }
    .nav.nav-tabs.bg-success > .nav-item > .nav-link.active {
      border: 1px solid #fff;
      border-radius: 30px; }
  .nav.nav-tabs.bg-info > .nav-item > .nav-link {
    background-color: transparent;
    color: #fff; }
    .nav.nav-tabs.bg-info > .nav-item > .nav-link.active {
      border: 1px solid #fff;
      border-radius: 30px; }
  .nav.nav-tabs.bg-warning > .nav-item > .nav-link {
    background-color: transparent;
    color: #fff; }
    .nav.nav-tabs.bg-warning > .nav-item > .nav-link.active {
      border: 1px solid #fff;
      border-radius: 30px; }
  .nav.nav-tabs.bg-danger > .nav-item > .nav-link {
    background-color: transparent;
    color: #fff; }
    .nav.nav-tabs.bg-danger > .nav-item > .nav-link.active {
      border: 1px solid #fff;
      border-radius: 30px; }
  .nav.nav-tabs.bg-light > .nav-item > .nav-link {
    background-color: transparent;
    color: #888; }
    .nav.nav-tabs.bg-light > .nav-item > .nav-link.active {
      border: 1px solid #888;
      border-radius: 30px; }
  .nav.nav-tabs.bg-dark > .nav-item > .nav-link {
    background-color: transparent;
    color: #fff; }
    .nav.nav-tabs.bg-dark > .nav-item > .nav-link.active {
      border: 1px solid #fff;
      border-radius: 30px; }
  .nav.nav-tabs.bg-gray > .nav-item > .nav-link {
    background-color: transparent;
    color: #888; }
    .nav.nav-tabs.bg-gray > .nav-item > .nav-link.active {
      border: 1px solid #888;
      border-radius: 30px; }

.nav.nav-pills .nav-item {
  margin-right: 15px; }
  .nav.nav-pills .nav-item.circle .nav-link {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 60px;
    height: 60px;
    overflow: hidden;
    border-radius: 120px; }
  .nav.nav-pills .nav-item .nav-link {
    background-color: rgba(222, 222, 222, 0.3);
    color: #9a9a9a; }
    .nav.nav-pills .nav-item .nav-link.active {
      background-color: #f96332;
      color: white;
      box-shadow: 0px 5px 35px 0px rgba(0, 0, 0, 0.3); }

.nav.nav-pills.flex-column .nav-item {
  margin-right: 0px;
  margin-bottom: 15px; }

.nav.nav-pills i {
  font-size: 20px;
  line-height: 30px; }

.navbar {
  transition: all 0.5s;
  transition-delay: 0.25s;
  box-shadow: 0px 0px 20px 0px rgba(0, 0, 0, 0.15); }
  .navbar.navbar-ontop {
    background-color: transparent !important;
    padding-top: 20px;
    box-shadow: none !important; }
  .navbar .nav-item .nav-link {
    font-size: 10px;
    transition: background-color 0.4s;
    border-radius: 3px;
    padding-top: 11px;
    padding-bottom: 11px;
    line-height: 21px; }
    .navbar .nav-item .nav-link:hover {
      background-color: rgba(255, 255, 255, 0.2); }
    .navbar .nav-item .nav-link.active {
      background-color: rgba(255, 255, 255, 0.2); }
  .navbar.transparent {
    box-shadow: none !important; }
  .navbar .btn {
    padding-top: 11px;
    padding-bottom: 11px;
    line-height: 21px;
    border: none; }

.btn {
  font-size: 0.74375rem; }
  .btn.btn-primary {
    color: #fff;
    background-color: #f96332;
    border-color: transparent; }
    .btn.btn-primary:hover {
      color: #fff;
      background-color: #fa7f57;
      border-color: transparent; }
    .btn.btn-primary:focus, .btn.btn-primary.focus {
      box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-primary.disabled, .btn.btn-primary:disabled {
      color: #fff;
      background-color: #f96332;
      border-color: transparent; }
    .btn.btn-primary:not(:disabled):not(.disabled):active, .btn.btn-primary:not(:disabled):not(.disabled).active,
    .show > .btn.btn-primary.dropdown-toggle {
      color: #fff;
      background-color: #fa7f57;
      border-color: transparent; }
      .btn.btn-primary:not(:disabled):not(.disabled):active:focus, .btn.btn-primary:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-primary.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-primary:not(:disabled):not(.disabled):hover {
      box-shadow: 0 3px 8px 0 rgba(0, 0, 0, 0.2); }
    .btn.btn-primary:disabled:focus, .btn.btn-primary.disabled:focus {
      box-shadow: none !important; }
    .btn.btn-primary:not(:disabled):not(.disabled):active:focus, .btn.btn-primary:not(:hover):focus {
      background-color: #fa7f57;
      box-shadow: none !important; }
  .btn.btn-outline-primary {
    color: #f96332;
    background-color: transparent;
    background-image: none;
    border-color: #f96332;
    box-shadow: none !important; }
    .btn.btn-outline-primary:hover {
      color: #f96332;
      background-color: transparent;
      border-color: #f96332; }
    .btn.btn-outline-primary:focus, .btn.btn-outline-primary.focus {
      box-shadow: 0 0 0 0.2rem rgba(249, 99, 50, 0.5); }
    .btn.btn-outline-primary.disabled, .btn.btn-outline-primary:disabled {
      color: #f96332;
      background-color: transparent; }
    .btn.btn-outline-primary:not(:disabled):not(.disabled):active, .btn.btn-outline-primary:not(:disabled):not(.disabled).active,
    .show > .btn.btn-outline-primary.dropdown-toggle {
      color: #fff;
      background-color: transparent;
      border-color: #f96332; }
      .btn.btn-outline-primary:not(:disabled):not(.disabled):active:focus, .btn.btn-outline-primary:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-outline-primary.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(249, 99, 50, 0.5); }
    .btn.btn-outline-primary:active {
      color: #f96332 !important; }
  .btn.btn-secondary {
    color: #fff;
    background-color: #888;
    border-color: transparent; }
    .btn.btn-secondary:hover {
      color: #fff;
      background-color: #9b9b9b;
      border-color: transparent; }
    .btn.btn-secondary:focus, .btn.btn-secondary.focus {
      box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-secondary.disabled, .btn.btn-secondary:disabled {
      color: #fff;
      background-color: #888;
      border-color: transparent; }
    .btn.btn-secondary:not(:disabled):not(.disabled):active, .btn.btn-secondary:not(:disabled):not(.disabled).active,
    .show > .btn.btn-secondary.dropdown-toggle {
      color: #fff;
      background-color: #9b9b9b;
      border-color: transparent; }
      .btn.btn-secondary:not(:disabled):not(.disabled):active:focus, .btn.btn-secondary:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-secondary.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-secondary:not(:disabled):not(.disabled):hover {
      box-shadow: 0 3px 8px 0 rgba(0, 0, 0, 0.2); }
    .btn.btn-secondary:disabled:focus, .btn.btn-secondary.disabled:focus {
      box-shadow: none !important; }
    .btn.btn-secondary:not(:disabled):not(.disabled):active:focus, .btn.btn-secondary:not(:hover):focus {
      background-color: #9b9b9b;
      box-shadow: none !important; }
  .btn.btn-outline-secondary {
    color: #888;
    background-color: transparent;
    background-image: none;
    border-color: #888;
    box-shadow: none !important; }
    .btn.btn-outline-secondary:hover {
      color: #888;
      background-color: transparent;
      border-color: #888; }
    .btn.btn-outline-secondary:focus, .btn.btn-outline-secondary.focus {
      box-shadow: 0 0 0 0.2rem rgba(136, 136, 136, 0.5); }
    .btn.btn-outline-secondary.disabled, .btn.btn-outline-secondary:disabled {
      color: #888;
      background-color: transparent; }
    .btn.btn-outline-secondary:not(:disabled):not(.disabled):active, .btn.btn-outline-secondary:not(:disabled):not(.disabled).active,
    .show > .btn.btn-outline-secondary.dropdown-toggle {
      color: #fff;
      background-color: transparent;
      border-color: #888; }
      .btn.btn-outline-secondary:not(:disabled):not(.disabled):active:focus, .btn.btn-outline-secondary:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-outline-secondary.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(136, 136, 136, 0.5); }
    .btn.btn-outline-secondary:active {
      color: #888 !important; }
  .btn.btn-success {
    color: #fff;
    background-color: #18ce0f;
    border-color: transparent; }
    .btn.btn-success:hover {
      color: #fff;
      background-color: #1fee15;
      border-color: transparent; }
    .btn.btn-success:focus, .btn.btn-success.focus {
      box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-success.disabled, .btn.btn-success:disabled {
      color: #fff;
      background-color: #18ce0f;
      border-color: transparent; }
    .btn.btn-success:not(:disabled):not(.disabled):active, .btn.btn-success:not(:disabled):not(.disabled).active,
    .show > .btn.btn-success.dropdown-toggle {
      color: #fff;
      background-color: #1fee15;
      border-color: transparent; }
      .btn.btn-success:not(:disabled):not(.disabled):active:focus, .btn.btn-success:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-success.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-success:not(:disabled):not(.disabled):hover {
      box-shadow: 0 3px 8px 0 rgba(0, 0, 0, 0.2); }
    .btn.btn-success:disabled:focus, .btn.btn-success.disabled:focus {
      box-shadow: none !important; }
    .btn.btn-success:not(:disabled):not(.disabled):active:focus, .btn.btn-success:not(:hover):focus {
      background-color: #1fee15;
      box-shadow: none !important; }
  .btn.btn-outline-success {
    color: #18ce0f;
    background-color: transparent;
    background-image: none;
    border-color: #18ce0f;
    box-shadow: none !important; }
    .btn.btn-outline-success:hover {
      color: #18ce0f;
      background-color: transparent;
      border-color: #18ce0f; }
    .btn.btn-outline-success:focus, .btn.btn-outline-success.focus {
      box-shadow: 0 0 0 0.2rem rgba(24, 206, 15, 0.5); }
    .btn.btn-outline-success.disabled, .btn.btn-outline-success:disabled {
      color: #18ce0f;
      background-color: transparent; }
    .btn.btn-outline-success:not(:disabled):not(.disabled):active, .btn.btn-outline-success:not(:disabled):not(.disabled).active,
    .show > .btn.btn-outline-success.dropdown-toggle {
      color: #fff;
      background-color: transparent;
      border-color: #18ce0f; }
      .btn.btn-outline-success:not(:disabled):not(.disabled):active:focus, .btn.btn-outline-success:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-outline-success.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(24, 206, 15, 0.5); }
    .btn.btn-outline-success:active {
      color: #18ce0f !important; }
  .btn.btn-info {
    color: #fff;
    background-color: #2CA8FF;
    border-color: transparent; }
    .btn.btn-info:hover {
      color: #fff;
      background-color: #52b8ff;
      border-color: transparent; }
    .btn.btn-info:focus, .btn.btn-info.focus {
      box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-info.disabled, .btn.btn-info:disabled {
      color: #fff;
      background-color: #2CA8FF;
      border-color: transparent; }
    .btn.btn-info:not(:disabled):not(.disabled):active, .btn.btn-info:not(:disabled):not(.disabled).active,
    .show > .btn.btn-info.dropdown-toggle {
      color: #fff;
      background-color: #52b8ff;
      border-color: transparent; }
      .btn.btn-info:not(:disabled):not(.disabled):active:focus, .btn.btn-info:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-info.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-info:not(:disabled):not(.disabled):hover {
      box-shadow: 0 3px 8px 0 rgba(0, 0, 0, 0.2); }
    .btn.btn-info:disabled:focus, .btn.btn-info.disabled:focus {
      box-shadow: none !important; }
    .btn.btn-info:not(:disabled):not(.disabled):active:focus, .btn.btn-info:not(:hover):focus {
      background-color: #52b8ff;
      box-shadow: none !important; }
  .btn.btn-outline-info {
    color: #2CA8FF;
    background-color: transparent;
    background-image: none;
    border-color: #2CA8FF;
    box-shadow: none !important; }
    .btn.btn-outline-info:hover {
      color: #2CA8FF;
      background-color: transparent;
      border-color: #2CA8FF; }
    .btn.btn-outline-info:focus, .btn.btn-outline-info.focus {
      box-shadow: 0 0 0 0.2rem rgba(44, 168, 255, 0.5); }
    .btn.btn-outline-info.disabled, .btn.btn-outline-info:disabled {
      color: #2CA8FF;
      background-color: transparent; }
    .btn.btn-outline-info:not(:disabled):not(.disabled):active, .btn.btn-outline-info:not(:disabled):not(.disabled).active,
    .show > .btn.btn-outline-info.dropdown-toggle {
      color: #fff;
      background-color: transparent;
      border-color: #2CA8FF; }
      .btn.btn-outline-info:not(:disabled):not(.disabled):active:focus, .btn.btn-outline-info:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-outline-info.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(44, 168, 255, 0.5); }
    .btn.btn-outline-info:active {
      color: #2CA8FF !important; }
  .btn.btn-warning {
    color: #fff;
    background-color: #FFB236;
    border-color: transparent; }
    .btn.btn-warning:hover {
      color: #fff;
      background-color: #ffc15c;
      border-color: transparent; }
    .btn.btn-warning:focus, .btn.btn-warning.focus {
      box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-warning.disabled, .btn.btn-warning:disabled {
      color: #fff;
      background-color: #FFB236;
      border-color: transparent; }
    .btn.btn-warning:not(:disabled):not(.disabled):active, .btn.btn-warning:not(:disabled):not(.disabled).active,
    .show > .btn.btn-warning.dropdown-toggle {
      color: #fff;
      background-color: #ffc15c;
      border-color: transparent; }
      .btn.btn-warning:not(:disabled):not(.disabled):active:focus, .btn.btn-warning:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-warning.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-warning:not(:disabled):not(.disabled):hover {
      box-shadow: 0 3px 8px 0 rgba(0, 0, 0, 0.2); }
    .btn.btn-warning:disabled:focus, .btn.btn-warning.disabled:focus {
      box-shadow: none !important; }
    .btn.btn-warning:not(:disabled):not(.disabled):active:focus, .btn.btn-warning:not(:hover):focus {
      background-color: #ffc15c;
      box-shadow: none !important; }
  .btn.btn-outline-warning {
    color: #FFB236;
    background-color: transparent;
    background-image: none;
    border-color: #FFB236;
    box-shadow: none !important; }
    .btn.btn-outline-warning:hover {
      color: #FFB236;
      background-color: transparent;
      border-color: #FFB236; }
    .btn.btn-outline-warning:focus, .btn.btn-outline-warning.focus {
      box-shadow: 0 0 0 0.2rem rgba(255, 178, 54, 0.5); }
    .btn.btn-outline-warning.disabled, .btn.btn-outline-warning:disabled {
      color: #FFB236;
      background-color: transparent; }
    .btn.btn-outline-warning:not(:disabled):not(.disabled):active, .btn.btn-outline-warning:not(:disabled):not(.disabled).active,
    .show > .btn.btn-outline-warning.dropdown-toggle {
      color: #fff;
      background-color: transparent;
      border-color: #FFB236; }
      .btn.btn-outline-warning:not(:disabled):not(.disabled):active:focus, .btn.btn-outline-warning:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-outline-warning.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(255, 178, 54, 0.5); }
    .btn.btn-outline-warning:active {
      color: #FFB236 !important; }
  .btn.btn-danger {
    color: #fff;
    background-color: #FF3636;
    border-color: transparent; }
    .btn.btn-danger:hover {
      color: #fff;
      background-color: #ff5c5c;
      border-color: transparent; }
    .btn.btn-danger:focus, .btn.btn-danger.focus {
      box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-danger.disabled, .btn.btn-danger:disabled {
      color: #fff;
      background-color: #FF3636;
      border-color: transparent; }
    .btn.btn-danger:not(:disabled):not(.disabled):active, .btn.btn-danger:not(:disabled):not(.disabled).active,
    .show > .btn.btn-danger.dropdown-toggle {
      color: #fff;
      background-color: #ff5c5c;
      border-color: transparent; }
      .btn.btn-danger:not(:disabled):not(.disabled):active:focus, .btn.btn-danger:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-danger.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-danger:not(:disabled):not(.disabled):hover {
      box-shadow: 0 3px 8px 0 rgba(0, 0, 0, 0.2); }
    .btn.btn-danger:disabled:focus, .btn.btn-danger.disabled:focus {
      box-shadow: none !important; }
    .btn.btn-danger:not(:disabled):not(.disabled):active:focus, .btn.btn-danger:not(:hover):focus {
      background-color: #ff5c5c;
      box-shadow: none !important; }
  .btn.btn-outline-danger {
    color: #FF3636;
    background-color: transparent;
    background-image: none;
    border-color: #FF3636;
    box-shadow: none !important; }
    .btn.btn-outline-danger:hover {
      color: #FF3636;
      background-color: transparent;
      border-color: #FF3636; }
    .btn.btn-outline-danger:focus, .btn.btn-outline-danger.focus {
      box-shadow: 0 0 0 0.2rem rgba(255, 54, 54, 0.5); }
    .btn.btn-outline-danger.disabled, .btn.btn-outline-danger:disabled {
      color: #FF3636;
      background-color: transparent; }
    .btn.btn-outline-danger:not(:disabled):not(.disabled):active, .btn.btn-outline-danger:not(:disabled):not(.disabled).active,
    .show > .btn.btn-outline-danger.dropdown-toggle {
      color: #fff;
      background-color: transparent;
      border-color: #FF3636; }
      .btn.btn-outline-danger:not(:disabled):not(.disabled):active:focus, .btn.btn-outline-danger:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-outline-danger.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(255, 54, 54, 0.5); }
    .btn.btn-outline-danger:active {
      color: #FF3636 !important; }
  .btn.btn-light {
    color: #888;
    background-color: #FFFFFF;
    border-color: transparent; }
    .btn.btn-light:hover {
      color: #888;
      background-color: white;
      border-color: transparent; }
    .btn.btn-light:focus, .btn.btn-light.focus {
      box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-light.disabled, .btn.btn-light:disabled {
      color: #888;
      background-color: #FFFFFF;
      border-color: transparent; }
    .btn.btn-light:not(:disabled):not(.disabled):active, .btn.btn-light:not(:disabled):not(.disabled).active,
    .show > .btn.btn-light.dropdown-toggle {
      color: #888;
      background-color: white;
      border-color: transparent; }
      .btn.btn-light:not(:disabled):not(.disabled):active:focus, .btn.btn-light:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-light.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-light:not(:disabled):not(.disabled):hover {
      box-shadow: 0 3px 8px 0 rgba(0, 0, 0, 0.2); }
    .btn.btn-light:disabled:focus, .btn.btn-light.disabled:focus {
      box-shadow: none !important; }
    .btn.btn-light:not(:disabled):not(.disabled):active:focus, .btn.btn-light:not(:hover):focus {
      background-color: white;
      box-shadow: none !important; }
  .btn.btn-outline-light {
    color: #FFFFFF;
    background-color: transparent;
    background-image: none;
    border-color: #FFFFFF;
    box-shadow: none !important; }
    .btn.btn-outline-light:hover {
      color: #FFFFFF;
      background-color: transparent;
      border-color: #FFFFFF; }
    .btn.btn-outline-light:focus, .btn.btn-outline-light.focus {
      box-shadow: 0 0 0 0.2rem rgba(255, 255, 255, 0.5); }
    .btn.btn-outline-light.disabled, .btn.btn-outline-light:disabled {
      color: #FFFFFF;
      background-color: transparent; }
    .btn.btn-outline-light:not(:disabled):not(.disabled):active, .btn.btn-outline-light:not(:disabled):not(.disabled).active,
    .show > .btn.btn-outline-light.dropdown-toggle {
      color: #fff;
      background-color: transparent;
      border-color: #FFFFFF; }
      .btn.btn-outline-light:not(:disabled):not(.disabled):active:focus, .btn.btn-outline-light:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-outline-light.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(255, 255, 255, 0.5); }
    .btn.btn-outline-light:active {
      color: #FFFFFF !important; }
  .btn.btn-dark {
    color: #fff;
    background-color: #2c2c2c;
    border-color: transparent; }
    .btn.btn-dark:hover {
      color: #fff;
      background-color: #3f3f3f;
      border-color: transparent; }
    .btn.btn-dark:focus, .btn.btn-dark.focus {
      box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-dark.disabled, .btn.btn-dark:disabled {
      color: #fff;
      background-color: #2c2c2c;
      border-color: transparent; }
    .btn.btn-dark:not(:disabled):not(.disabled):active, .btn.btn-dark:not(:disabled):not(.disabled).active,
    .show > .btn.btn-dark.dropdown-toggle {
      color: #fff;
      background-color: #3f3f3f;
      border-color: transparent; }
      .btn.btn-dark:not(:disabled):not(.disabled):active:focus, .btn.btn-dark:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-dark.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-dark:not(:disabled):not(.disabled):hover {
      box-shadow: 0 3px 8px 0 rgba(0, 0, 0, 0.2); }
    .btn.btn-dark:disabled:focus, .btn.btn-dark.disabled:focus {
      box-shadow: none !important; }
    .btn.btn-dark:not(:disabled):not(.disabled):active:focus, .btn.btn-dark:not(:hover):focus {
      background-color: #3f3f3f;
      box-shadow: none !important; }
  .btn.btn-outline-dark {
    color: #2c2c2c;
    background-color: transparent;
    background-image: none;
    border-color: #2c2c2c;
    box-shadow: none !important; }
    .btn.btn-outline-dark:hover {
      color: #2c2c2c;
      background-color: transparent;
      border-color: #2c2c2c; }
    .btn.btn-outline-dark:focus, .btn.btn-outline-dark.focus {
      box-shadow: 0 0 0 0.2rem rgba(44, 44, 44, 0.5); }
    .btn.btn-outline-dark.disabled, .btn.btn-outline-dark:disabled {
      color: #2c2c2c;
      background-color: transparent; }
    .btn.btn-outline-dark:not(:disabled):not(.disabled):active, .btn.btn-outline-dark:not(:disabled):not(.disabled).active,
    .show > .btn.btn-outline-dark.dropdown-toggle {
      color: #fff;
      background-color: transparent;
      border-color: #2c2c2c; }
      .btn.btn-outline-dark:not(:disabled):not(.disabled):active:focus, .btn.btn-outline-dark:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-outline-dark.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(44, 44, 44, 0.5); }
    .btn.btn-outline-dark:active {
      color: #2c2c2c !important; }
  .btn.btn-gray {
    color: #888;
    background-color: #EEEEEE;
    border-color: transparent; }
    .btn.btn-gray:hover {
      color: #888;
      background-color: white;
      border-color: transparent; }
    .btn.btn-gray:focus, .btn.btn-gray.focus {
      box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-gray.disabled, .btn.btn-gray:disabled {
      color: #888;
      background-color: #EEEEEE;
      border-color: transparent; }
    .btn.btn-gray:not(:disabled):not(.disabled):active, .btn.btn-gray:not(:disabled):not(.disabled).active,
    .show > .btn.btn-gray.dropdown-toggle {
      color: #888;
      background-color: white;
      border-color: transparent; }
      .btn.btn-gray:not(:disabled):not(.disabled):active:focus, .btn.btn-gray:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-gray.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(0, 0, 0, 0.5); }
    .btn.btn-gray:not(:disabled):not(.disabled):hover {
      box-shadow: 0 3px 8px 0 rgba(0, 0, 0, 0.2); }
    .btn.btn-gray:disabled:focus, .btn.btn-gray.disabled:focus {
      box-shadow: none !important; }
    .btn.btn-gray:not(:disabled):not(.disabled):active:focus, .btn.btn-gray:not(:hover):focus {
      background-color: white;
      box-shadow: none !important; }
  .btn.btn-outline-gray {
    color: #EEEEEE;
    background-color: transparent;
    background-image: none;
    border-color: #EEEEEE;
    box-shadow: none !important; }
    .btn.btn-outline-gray:hover {
      color: #EEEEEE;
      background-color: transparent;
      border-color: #EEEEEE; }
    .btn.btn-outline-gray:focus, .btn.btn-outline-gray.focus {
      box-shadow: 0 0 0 0.2rem rgba(238, 238, 238, 0.5); }
    .btn.btn-outline-gray.disabled, .btn.btn-outline-gray:disabled {
      color: #EEEEEE;
      background-color: transparent; }
    .btn.btn-outline-gray:not(:disabled):not(.disabled):active, .btn.btn-outline-gray:not(:disabled):not(.disabled).active,
    .show > .btn.btn-outline-gray.dropdown-toggle {
      color: #fff;
      background-color: transparent;
      border-color: #EEEEEE; }
      .btn.btn-outline-gray:not(:disabled):not(.disabled):active:focus, .btn.btn-outline-gray:not(:disabled):not(.disabled).active:focus,
      .show > .btn.btn-outline-gray.dropdown-toggle:focus {
        box-shadow: 0 0 0 0.2rem rgba(238, 238, 238, 0.5); }
    .btn.btn-outline-gray:active {
      color: #EEEEEE !important; }

h6 {
  font-weight: 700; }

img.rounded {
  border-radius: .25rem !important; }

.carousel {
  box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.3); }
  .carousel .carousel-caption > * {
    margin-bottom: 15px; }

.card {
  box-shadow: 0px 5px 25px 0px rgba(0, 0, 0, 0.2); }

.modal .modal-content {
  box-shadow: 0px 5px 25px 0px rgba(0, 0, 0, 0.2); }

form .form-control {
  font-size: 0.74375rem; }

form .form-group.is-valid:after {
  font-family: Nucleo Outline;
  content: "\ea22";
  display: inline-block;
  position: absolute;
  right: 30px;
  top: calc((2.29rem / 2) - 1.4rem / 2);
  color: #18ce0f; }

form .form-group.is-invalid > * {
  border-color: rgba(255, 54, 54, 0.3);
  background: rgba(44, 44, 44, 0.02);
  color: #FF3636; }

form .form-group.is-invalid:after {
  font-family: Nucleo Outline;
  content: "\ea53";
  display: inline-block;
  position: absolute;
  right: 30px;
  top: calc((2.29rem / 2) - 1.4rem / 2);
  color: #FF3636; }

.input-group {
  background-color: rgba(255, 255, 255, 0.1);
  border-radius: 2.5rem;
  border: 1px solid #ced4da;
  transition: all 0.3s; }
  .input-group .input-group-prepend span, .input-group .form-control {
    background: transparent; }
  .input-group.focus {
    background-color: rgba(255, 255, 255, 0.4); }
  .input-group * {
    border: none; }
  .input-group .input-group-append span {
    padding-left: 0; }
  .input-group .input-group-prepend span {
    padding-right: 0; }

.custom-control .custom-control-label {
  padding-left: 5px;
  line-height: 26px; }

.custom-control .custom-control-label::before {
  border: 1px solid #E3E3E3; }

.custom-control .custom-control-label::after {
  transition: opacity .3s;
  opacity: 0;
  color: #555; }

.custom-control .custom-control-input:checked ~ .custom-control-label::after {
  opacity: 1; }

.custom-control .custom-control-input:disabled ~ .custom-control-label::before {
  opacity: .4; }

.custom-control .custom-control-input:disabled ~ .custom-control-label::after {
  opacity: .4; }

.custom-control.custom-select {
  appearance: none !important;
  -webkit-appearance: none !important; }

.custom-control.custom-checkbox .custom-control-label {
  padding-left: 40px; }

.custom-control.custom-checkbox .custom-control-label::before {
  top: 0;
  width: 26px;
  height: 26px;
  border: 1px solid #E3E3E3;
  border-radius: 0.25rem; }

.custom-control.custom-checkbox .custom-control-input:checked ~ .custom-control-label::after {
  border-radius: 0.25rem;
  top: 0;
  left: 6px;
  font-family: 'Nucleo Outline';
  content: "\ea22"; }

.custom-control.custom-radio {
  margin-bottom: 1rem; }

.dropdown-menu {
  border: none;
  box-shadow: 0px 10px 50px 0px rgba(0, 0, 0, 0.2); }
  .dropdown-menu:before {
    display: inline-block;
    position: absolute;
    width: 0;
    height: 0;
    vertical-align: middle;
    content: "";
    top: -5px;
    left: 10px;
    right: auto;
    color: #FFFFFF;
    border-bottom: .4em solid;
    border-right: .4em solid transparent;
    border-left: .4em solid transparent; }
  .dropdown-menu:before {
    display: inline-block;
    position: absolute;
    width: 0;
    height: 0;
    vertical-align: middle;
    content: "";
    top: -5px;
    left: auto;
    right: 10px;
    color: #FFFFFF;
    border-bottom: .4em solid;
    border-right: .4em solid transparent;
    border-left: .4em solid transparent; }
  .dropdown-menu .dropdown-item {
    font-size: 0.8571em; }

.pagination .page-item {
  background-color: transparent !important; }

.pagination .page-item .page-link {
  border: 0;
  border-radius: 30px;
  color: #2c2c2c;
  padding: 0px 11px;
  margin: 0 3px;
  min-width: 30px;
  text-align: center;
  height: 30px;
  line-height: 30px; }

.pagination .disabled > a {
  color: #888 !important; }

.pagination .page-item.bg-primary > a {
  background-color: #f96332;
  border-radius: 30px !important; }

.pagination .page-item.bg-secondary > a {
  background-color: #888;
  border-radius: 30px !important; }

.pagination .page-item.bg-success > a {
  background-color: #18ce0f;
  border-radius: 30px !important; }

.pagination .page-item.bg-info > a {
  background-color: #2CA8FF;
  border-radius: 30px !important; }

.pagination .page-item.bg-warning > a {
  background-color: #FFB236;
  border-radius: 30px !important; }

.pagination .page-item.bg-danger > a {
  background-color: #FF3636;
  border-radius: 30px !important; }

.pagination .page-item.bg-light > a {
  background-color: #FFFFFF;
  border-radius: 30px !important; }

.pagination .page-item.bg-dark > a {
  background-color: #2c2c2c;
  border-radius: 30px !important; }

.pagination .page-item.bg-gray > a {
  background-color: #EEEEEE;
  border-radius: 30px !important; }

.pagination .active > a {
  color: white !important;
  box-shadow: 0px 5px 35px 0px rgba(0, 0, 0, 0.3); }

.badge.badge.badge-primary {
  background-color: white;
  color: #f96332;
  border: 1px solid #f96332;
  line-height: 12px;
  margin-bottom: 5px;
  border-radius: 0.875rem;
  padding-bottom: .25rem;
  padding-top: .25rem; }

.badge.badge.badge-secondary {
  background-color: white;
  color: #888;
  border: 1px solid #888;
  line-height: 12px;
  margin-bottom: 5px;
  border-radius: 0.875rem;
  padding-bottom: .25rem;
  padding-top: .25rem; }

.badge.badge.badge-success {
  background-color: white;
  color: #18ce0f;
  border: 1px solid #18ce0f;
  line-height: 12px;
  margin-bottom: 5px;
  border-radius: 0.875rem;
  padding-bottom: .25rem;
  padding-top: .25rem; }

.badge.badge.badge-info {
  background-color: white;
  color: #2CA8FF;
  border: 1px solid #2CA8FF;
  line-height: 12px;
  margin-bottom: 5px;
  border-radius: 0.875rem;
  padding-bottom: .25rem;
  padding-top: .25rem; }

.badge.badge.badge-warning {
  background-color: white;
  color: #FFB236;
  border: 1px solid #FFB236;
  line-height: 12px;
  margin-bottom: 5px;
  border-radius: 0.875rem;
  padding-bottom: .25rem;
  padding-top: .25rem; }

.badge.badge.badge-danger {
  background-color: white;
  color: #FF3636;
  border: 1px solid #FF3636;
  line-height: 12px;
  margin-bottom: 5px;
  border-radius: 0.875rem;
  padding-bottom: .25rem;
  padding-top: .25rem; }

.badge.badge.badge-light {
  background-color: white;
  color: #FFFFFF;
  border: 1px solid #FFFFFF;
  line-height: 12px;
  margin-bottom: 5px;
  border-radius: 0.875rem;
  padding-bottom: .25rem;
  padding-top: .25rem; }

.badge.badge.badge-dark {
  background-color: white;
  color: #2c2c2c;
  border: 1px solid #2c2c2c;
  line-height: 12px;
  margin-bottom: 5px;
  border-radius: 0.875rem;
  padding-bottom: .25rem;
  padding-top: .25rem; }

.badge.badge.badge-gray {
  background-color: white;
  color: #EEEEEE;
  border: 1px solid #EEEEEE;
  line-height: 12px;
  margin-bottom: 5px;
  border-radius: 0.875rem;
  padding-bottom: .25rem;
  padding-top: .25rem; }

.alert.alert-primary {
  background-color: #f96332;
  opacity: 0.8; }

.alert.alert-secondary {
  background-color: #888;
  opacity: 0.8; }

.alert.alert-success {
  background-color: #18ce0f;
  opacity: 0.8; }

.alert.alert-info {
  background-color: #2CA8FF;
  opacity: 0.8; }

.alert.alert-warning {
  background-color: #FFB236;
  opacity: 0.8; }

.alert.alert-danger {
  background-color: #FF3636;
  opacity: 0.8; }

.alert.alert-light {
  background-color: #FFFFFF;
  opacity: 0.8; }

.alert.alert-dark {
  background-color: #2c2c2c;
  opacity: 0.8; }

.alert.alert-gray {
  background-color: #EEEEEE;
  opacity: 0.8; }

.blockquote {
  border-left: none;
  border: 1px solid #888;
  padding: 20px;
  font-size: 1.1em;
  line-height: 1.8; }
  .blockquote.blockquote-primary {
    border-color: #f96332 !important;
    color: #f96332 !important; }
  .blockquote.blockquote-primary > .blockquote-footer {
    color: #f96332 !important; }
  .blockquote.blockquote-secondary {
    border-color: #888 !important;
    color: #888 !important; }
  .blockquote.blockquote-secondary > .blockquote-footer {
    color: #888 !important; }
  .blockquote.blockquote-success {
    border-color: #18ce0f !important;
    color: #18ce0f !important; }
  .blockquote.blockquote-success > .blockquote-footer {
    color: #18ce0f !important; }
  .blockquote.blockquote-info {
    border-color: #2CA8FF !important;
    color: #2CA8FF !important; }
  .blockquote.blockquote-info > .blockquote-footer {
    color: #2CA8FF !important; }
  .blockquote.blockquote-warning {
    border-color: #FFB236 !important;
    color: #FFB236 !important; }
  .blockquote.blockquote-warning > .blockquote-footer {
    color: #FFB236 !important; }
  .blockquote.blockquote-danger {
    border-color: #FF3636 !important;
    color: #FF3636 !important; }
  .blockquote.blockquote-danger > .blockquote-footer {
    color: #FF3636 !important; }
  .blockquote.blockquote-light {
    border-color: #FFFFFF !important;
    color: #FFFFFF !important; }
  .blockquote.blockquote-light > .blockquote-footer {
    color: #FFFFFF !important; }
  .blockquote.blockquote-dark {
    border-color: #2c2c2c !important;
    color: #2c2c2c !important; }
  .blockquote.blockquote-dark > .blockquote-footer {
    color: #2c2c2c !important; }
  .blockquote.blockquote-gray {
    border-color: #EEEEEE !important;
    color: #EEEEEE !important; }
  .blockquote.blockquote-gray > .blockquote-footer {
    color: #EEEEEE !important; }

.tooltip-inner {
  min-width: 130px;
  color: black;
  box-shadow: 0px 5px 25px 0px rgba(0, 0, 0, 0.2); }

.bg-primary {
  color: #fff; }
  .bg-primary input::placeholder {
    color: rgba(255, 255, 255, 0.8); }
  .bg-primary .input-group-text {
    color: #fff; }

.bg-secondary {
  color: #fff; }
  .bg-secondary input::placeholder {
    color: rgba(255, 255, 255, 0.8); }
  .bg-secondary .input-group-text {
    color: #fff; }

.bg-success {
  color: #fff; }
  .bg-success input::placeholder {
    color: rgba(255, 255, 255, 0.8); }
  .bg-success .input-group-text {
    color: #fff; }

.bg-info {
  color: #fff; }
  .bg-info input::placeholder {
    color: rgba(255, 255, 255, 0.8); }
  .bg-info .input-group-text {
    color: #fff; }

.bg-warning {
  color: #fff; }
  .bg-warning input::placeholder {
    color: rgba(255, 255, 255, 0.8); }
  .bg-warning .input-group-text {
    color: #fff; }

.bg-danger {
  color: #fff; }
  .bg-danger input::placeholder {
    color: rgba(255, 255, 255, 0.8); }
  .bg-danger .input-group-text {
    color: #fff; }

.bg-light {
  color: #888; }
  .bg-light input::placeholder {
    color: rgba(136, 136, 136, 0.8); }
  .bg-light .input-group-text {
    color: #888; }

.bg-dark {
  color: #fff; }
  .bg-dark input::placeholder {
    color: rgba(255, 255, 255, 0.8); }
  .bg-dark .input-group-text {
    color: #fff; }

.bg-gray {
  color: #888; }
  .bg-gray input::placeholder {
    color: rgba(136, 136, 136, 0.8); }
  .bg-gray .input-group-text {
    color: #888; }

.progress .progress-bar {
  color: transparent; }

.progress.progress.bg-primary {
  background: rgba(249, 99, 50, 0.3) !important; }
  .progress.progress.bg-primary .progress-bar {
    background: #f96332; }

.progress.progress.bg-secondary {
  background: rgba(136, 136, 136, 0.3) !important; }
  .progress.progress.bg-secondary .progress-bar {
    background: #888; }

.progress.progress.bg-success {
  background: rgba(24, 206, 15, 0.3) !important; }
  .progress.progress.bg-success .progress-bar {
    background: #18ce0f; }

.progress.progress.bg-info {
  background: rgba(44, 168, 255, 0.3) !important; }
  .progress.progress.bg-info .progress-bar {
    background: #2CA8FF; }

.progress.progress.bg-warning {
  background: rgba(255, 178, 54, 0.3) !important; }
  .progress.progress.bg-warning .progress-bar {
    background: #FFB236; }

.progress.progress.bg-danger {
  background: rgba(255, 54, 54, 0.3) !important; }
  .progress.progress.bg-danger .progress-bar {
    background: #FF3636; }

.progress.progress.bg-light {
  background: rgba(255, 255, 255, 0.3) !important; }
  .progress.progress.bg-light .progress-bar {
    background: #FFFFFF; }

.progress.progress.bg-dark {
  background: rgba(44, 44, 44, 0.3) !important; }
  .progress.progress.bg-dark .progress-bar {
    background: #2c2c2c; }

.progress.progress.bg-gray {
  background: rgba(238, 238, 238, 0.3) !important; }
  .progress.progress.bg-gray .progress-bar {
    background: #EEEEEE; }

html, body {
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased; }

.custom-toggle {
  height: 2.0rem;
  position: relative; }
  .custom-toggle .custom-control-label {
    padding-left: 70px;
    position: absolute; }
  .custom-toggle input {
    width: 60px;
    height: 22px;
    z-index: 1; }
  .custom-toggle .custom-control-input ~ .custom-control-label::before {
    background-color: transparent;
    width: 58px;
    height: 22px;
    border-radius: 30px;
    background: rgba(44, 44, 44, 0.2); }
  .custom-toggle .custom-control-input ~ .custom-control-label::after {
    height: 22px;
    width: 22px;
    border-radius: 30px;
    position: absolute;
    left: 0px;
    transition: all 0.5s;
    box-shadow: 0 1px 11px rgba(0, 0, 0, 0.25);
    background-color: rgba(23, 23, 23, 0.4);
    opacity: 1; }
  .custom-toggle .custom-control-input:checked ~ .custom-control-label::before {
    background: rgba(44, 44, 44, 0.2); }
  .custom-toggle .custom-control-input:checked ~ .custom-control-label::after {
    background-color: white !important;
    box-shadow: 0px 0px 4px #333;
    left: 40px; }

.custom-slider .custom-control-label::before {
  display: none; }

.custom-slider .custom-control-label::after {
  display: none; }

.custom-slider .slider {
  -webkit-appearance: none;
  appearance: none;
  height: 1px;
  background: #888;
  outline: none;
  opacity: 0.7;
  transition: opacity .3s; }

.custom-slider .slider::-webkit-slider-thumb:active {
  transform: scale3d(1.5, 1.5, 1); }

.custom-slider .slider::-webkit-slider-thumb {
  -webkit-appearance: none;
  appearance: none;
  width: 15px;
  height: 15px;
  border-radius: 15px;
  background: white;
  cursor: pointer;
  box-shadow: 0 1px 13px 0 rgba(0, 0, 0, 0.2);
  transition: all .3s; }

.custom-slider .noslider::-moz-range-thumb {
  width: 25px;
  height: 25px;
  background: #4CAF50;
  cursor: pointer; }

.custom-slider .noslider:hover {
  opacity: 1; }

.cover {
  min-height: 125%; }
  .cover .container {
    height: 100vh; }

.gradient-overlay {
  overflow: hidden;
  position: relative; }
  .gradient-overlay > *:first-child:before {
    content: '';
    width: 100%;
    height: 100%;
    display: block;
    position: absolute;
    left: 0px;
    top: 0px;
    pointer-events: none;
    background: linear-gradient(0deg, rgba(44, 44, 44, 0.2), rgba(224, 23, 3, 0.6)); }

.section-overlapping {
  margin-top: -100px; }

.btn-icon {
  height: calc(2.3rem + 2px);
  width: calc(2.3rem + 2px);
  border-radius: 50%;
  padding: 0px; }
  .btn-icon.btn-lg, .btn-group-lg > .btn-icon.btn {
    height: calc(3.4rem + 2px);
    width: calc(3.4rem + 2px); }
  .btn-icon.btn-sm, .btn-group-sm > .btn-icon.btn {
    height: calc(2rem + 2px);
    width: calc(2rem + 2px); }

.btn-twitter {
  color: #55acee !important; }

.btn-facebook {
  color: #344e86 !important; }

.btn-linkedin {
  color: #0077B5 !important; }

.btn-google {
  color: #dd4b39 !important; }

.rounded {
  border-radius: 30px !important; }

.datepicker.dropdown-menu {
  background-color: #f96332;
  color: white !important;
  font-size: 14px; }

.datepicker.dropdown-menu td:hover {
  color: black !important; }

.datepicker::after {
  border-top: 6px solid #f96332 !important; }

.datepicker td {
  padding: 7px !important; }
  .datepicker td.new, .datepicker td.old {
    color: rgba(255, 255, 255, 0.4) !important; }

/** shadow from 4.1 **/
.shadow-sm {
  box-shadow: 0 0.125rem 0.25rem rgba(0, 0, 0, 0.075) !important; }

.shadow {
  box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15) !important; }

.shadow-lg {
  box-shadow: 0 1rem 3rem rgba(0, 0, 0, 0.175) !important; }

.shadow-none {
  box-shadow: none !important; }
