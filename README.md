<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Nigel Li   |  Photography Portfolio</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	padding-inline-start: 0;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.page-description {
	margin-bottom: 2em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-default_background {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray_background {
	background: rgba(248, 248, 247, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(248, 243, 252, 1);
}
.highlight-pink_background {
	background: rgba(252, 241, 246, 1);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-default_background {
	color: inherit;
	fill: inherit;
}
.block-color-gray_background {
	background: rgba(248, 248, 247, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(248, 243, 252, 1);
}
.block-color-pink_background {
	background: rgba(252, 241, 246, 1);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-uiBlue { background-color: undefined; }
.select-value-color-pink { background-color: rgba(225, 136, 179, 0.27); }
.select-value-color-purple { background-color: rgba(168, 129, 197, 0.27); }
.select-value-color-green { background-color: rgba(123, 183, 129, 0.27); }
.select-value-color-gray { background-color: rgba(84, 72, 49, 0.15); }
.select-value-color-transparentGray { background-color: undefined; }
.select-value-color-translucentGray { background-color: undefined; }
.select-value-color-orange { background-color: rgba(224, 124, 57, 0.27); }
.select-value-color-brown { background-color: rgba(210, 162, 141, 0.35); }
.select-value-color-red { background-color: rgba(244, 171, 159, 0.4); }
.select-value-color-yellow { background-color: rgba(236, 191, 66, 0.39); }
.select-value-color-blue { background-color: rgba(93, 165, 206, 0.27); }
.select-value-color-pageGlass { background-color: undefined; }
.select-value-color-washGlass { background-color: undefined; }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="1a6a05dd-ba69-80c8-9e3f-c593326146fb" class="page serif"><header><img class="page-cover-image" src="_MG_5975_2.jpg" style="object-position:center 42.42%"/><div class="page-header-icon page-header-icon-with-cover"><span class="icon">📷</span></div><h1 class="page-title">Nigel Li   |  Photography Portfolio</h1><p class="page-description"></p></header><div class="page-body"><div id="1a6a05dd-ba69-81c3-921d-e979c7b9d737" class="column-list"><div id="1a6a05dd-ba69-80ad-9155-d4ca1592b6b6" style="width:16.666666666666664%" class="column"><figure id="1a6a05dd-ba69-8199-b7b8-c65a990382f6" class="image"><a href="2364eae1-86f6-4af6-a91c-b29f9265ff21.png"><img style="width:240px" src="2364eae1-86f6-4af6-a91c-b29f9265ff21.png"/></a></figure></div><div id="1a6a05dd-ba69-8190-b5fd-d1079e95fd46" style="width:54.166666666666664%" class="column"><p id="1a6a05dd-ba69-81fb-9df2-e0c7721fec9c" class="">I’m a photographer with over five years of experience in event, street and nature photography. From a young age, I developed a passion for capturing authentic moments and telling visual stories through my lens. My work focuses on blending creativity with technical skill to create compelling, high-quality images that evoke emotion and narrative from my perspective.</p></div><div id="1a6a05dd-ba69-80fb-a7fd-e89ca0904114" style="width:29.166666666666703%" class="column"><p id="1a6a05dd-ba69-805d-b711-e87e03154173" class=""><strong>📩 Contact Me</strong></p><p id="1a6a05dd-ba69-8051-9412-d7883428a5a8" class="">Have a project in mind or just want to connect? Feel free to reach out!<br/>📧 Email: <br/><a href="mailto:Nigel.Li@mail.utoronto.ca">Nigel.li@mail.utoronto.ca</a><br/>📷 Instagram: <br/><a href="https://www.instagram.com/nigel.li_">@nigel.li_</a></p></div></div><div id="1a6a05dd-ba69-8182-846f-d4087013ff0c" class="column-list"><div id="1a6a05dd-ba69-8198-9fcd-d8416765c300" style="width:50%" class="column"><h1 id="1a6a05dd-ba69-8154-ad9e-f9a66e992426" class="">Event Photography</h1></div><div id="1a6a05dd-ba69-8183-bd2c-e86c82888d56" style="width:50%" class="column"><p id="1a6a05dd-ba69-80cb-86d7-d242c0fde398" class="">
</p></div></div><h2 id="1a6a05dd-ba69-80f4-a71a-ed5aa33cf9ad" class="">Sports</h2><div id="1a6a05dd-ba69-8018-9107-d51c2e9629db" class="column-list"><div id="1a6a05dd-ba69-800b-b293-d0edcc6c50bb" style="width:45.83333333333333%" class="column"><figure id="1a6a05dd-ba69-8083-9f0c-e857f0d090ad" class="image"><a href="Terry_Fox_Photo1_Nigel_Li.jpg"><img style="width:960px" src="Terry_Fox_Photo1_Nigel_Li.jpg"/></a></figure></div><div id="1a6a05dd-ba69-8050-ba15-fdf9def49fec" style="width:29.166666666666664%" class="column"><figure id="1a6a05dd-ba69-809c-8d9b-d2499c79a26a" class="image"><a href="Terry_Fox_Photo4_Nigel_Li.jpg"><img style="width:384px" src="Terry_Fox_Photo4_Nigel_Li.jpg"/></a></figure><figure id="1a6a05dd-ba69-80b0-b91d-f94f268430f0" class="image"><a href="Terry_Fox_Photo2_Nigel_Li.jpg"><img style="width:340.15277099609375px" src="Terry_Fox_Photo2_Nigel_Li.jpg"/></a></figure></div><div id="1a6a05dd-ba69-80cb-b2d9-e2e38716011c" style="width:25.00000000000001%" class="column"><figure id="1a6a05dd-ba69-80e8-abdf-d0e0e9accff6" class="image"><a href="Terry_Fox_Photo3_Nigel_Li.jpg"><img style="width:432px" src="Terry_Fox_Photo3_Nigel_Li.jpg"/></a></figure></div></div><p id="1a6a05dd-ba69-8080-ae38-ea1aededd4ec" class="">
</p><div id="1a6a05dd-ba69-8015-a0f4-cf5aa1948810" class="column-list"><div id="1a6a05dd-ba69-807c-a7fa-d0529891fd69" style="width:41.666666666666664%" class="column"><figure id="1a6a05dd-ba69-8008-890e-e08a6fd936cf" class="image"><a href="Dodgeball_Photo3_Nigel_Li.jpg.jpg"><img style="width:576px" src="Dodgeball_Photo3_Nigel_Li.jpg.jpg"/></a></figure><p id="1a6a05dd-ba69-8060-96ea-ced4c1a6af62" class="">
</p></div><div id="1a6a05dd-ba69-80b0-8464-d9d74f2b86cc" style="width:20.833333333333332%" class="column"><figure id="1a6a05dd-ba69-8096-8a00-d1df1b882ea1" class="image"><a href="Dodgeball_Photo1_Nigel_Li.jpg.jpg"><img style="width:192px" src="Dodgeball_Photo1_Nigel_Li.jpg.jpg"/></a></figure></div><div id="1a6a05dd-ba69-80c3-9340-c2bd192bef69" style="width:37.500000000000036%" class="column"><figure id="1a6a05dd-ba69-80df-a3c1-f83576dd922f" class="image"><a href="Dodgeball_Photo2_Nigel_Li.jpg.jpg"><img style="width:624px" src="Dodgeball_Photo2_Nigel_Li.jpg.jpg"/></a></figure><p id="1a6a05dd-ba69-8017-b0f7-c91cb9ae0694" class="">
</p></div></div><h2 id="1a6a05dd-ba69-80d7-b8d6-d50fb4c95cd3" class="">Concerts</h2><div id="1a6a05dd-ba69-802a-9084-ee30e3ca2959" class="column-list"><div id="1a6a05dd-ba69-80d1-9ade-fd93a265795f" style="width:21.874999999999996%" class="column"><figure id="1a6a05dd-ba69-8071-b8c6-f34f87f7fa37" class="image"><a href="Concert_Photo1_Nigel_Li.jpg"><img style="width:432px" src="Concert_Photo1_Nigel_Li.jpg"/></a></figure></div><div id="1a6a05dd-ba69-80d8-97fa-d9131a4c653f" style="width:28.125%" class="column"><figure id="1a6a05dd-ba69-8045-9759-dc04d4333a4a" class="image"><a href="Concert_Photo2_Nigel_Li.jpg"><img style="width:432px" src="Concert_Photo2_Nigel_Li.jpg"/></a></figure></div><div id="1a6a05dd-ba69-80b9-a8b4-e93f1558e210" style="width:25%" class="column"><figure id="1a6a05dd-ba69-8019-ba19-cebff18a0cca" class="image"><a href="Concert_Photo3_Nigel_Li.jpg"><img style="width:528px" src="Concert_Photo3_Nigel_Li.jpg"/></a></figure></div><div id="1a6a05dd-ba69-80bd-a993-cc143f700e1b" style="width:25%" class="column"><figure id="1a6a05dd-ba69-80ce-ba3b-f9d451bfbba2" class="image"><a href="Concert_Photo4_Nigel_Li.jpg"><img style="width:2910px" src="Concert_Photo4_Nigel_Li.jpg"/></a></figure></div></div><h1 id="1a6a05dd-ba69-80e2-8954-dd8d3057f38f" class="">Street Photography</h1><div id="1a6a05dd-ba69-80f7-9019-ffad26d2a36d" class="column-list"><div id="1a6a05dd-ba69-8043-a12c-f5030444cd6c" style="width:25%" class="column"><figure id="1a6a05dd-ba69-80d2-a29d-ed07775cc723" class="image"><a href="Street_Photo2_Nigel_Li.jpg"><img style="width:624px" src="Street_Photo2_Nigel_Li.jpg"/></a></figure></div><div id="1a6a05dd-ba69-80e8-b7cf-c4867bc71071" style="width:50.83333333333333%" class="column"><figure id="1a6a05dd-ba69-8054-acf1-c2e4de183019" class="image"><a href="Street_Photo3_Nigel_Li.jpg"><img style="width:4912px" src="Street_Photo3_Nigel_Li.jpg"/></a></figure><p id="1a6a05dd-ba69-805d-8b30-f91a96e59e4b" class="">
</p></div><div id="1a6a05dd-ba69-8005-88c9-c97af31bb58f" style="width:24.16666666666666%" class="column"><figure id="1a6a05dd-ba69-802c-b04b-e6ccadd633dd" class="image"><a href="Street_Photo1_Nigel_Li.jpg"><img style="width:3348px" src="Street_Photo1_Nigel_Li.jpg"/></a></figure></div></div><h1 id="1a6a05dd-ba69-80c8-9a9f-eeaaccd952be" class="">Nature Photography</h1><div id="1a6a05dd-ba69-8032-af9c-ebd145f0751c" class="column-list"><div id="1a6a05dd-ba69-800b-a3a9-d612ff0af919" style="width:27.27272727272727%" class="column"><figure id="1a6a05dd-ba69-808a-9980-e9f59f319123" class="image"><a href="Nature_Photo1_Nigel_Li.jpg"><img style="width:288px" src="Nature_Photo1_Nigel_Li.jpg"/></a></figure></div><div id="1a6a05dd-ba69-8099-8e71-d83cf2398d9e" style="width:37.5%" class="column"><figure id="1a6a05dd-ba69-805a-ac46-e5b78233ff6b" class="image"><a href="Nature_Photo3_Nigel_Li.jpg"><img style="width:4737px" src="Nature_Photo3_Nigel_Li.jpg"/></a></figure></div><div id="1a6a05dd-ba69-808d-be76-c4989eb8b3b1" style="width:35.22727272727272%" class="column"><figure id="1a6a05dd-ba69-8073-83bc-e6ed12fdc7ba" class="image"><a href="Nature_Photo2_Nigel_Li.jpg"><img style="width:3509px" src="Nature_Photo2_Nigel_Li.jpg"/></a></figure></div></div><p id="1a6a05dd-ba69-80b9-a3ee-d204be61051b" class="">
</p></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>
