{"title":"Disabled","meta":{"title":"Disabled","description":"\n<p>Disable a Button by adding <code>disabled</code> attribute.</p>\n","order":"5"},"codes":{"jsx":"import { Button } from '@alifd/next';\n\nReactDOM.render(<div>\n    <Button type=\"primary\">Primary</Button>&nbsp;&nbsp;\n    <Button component=\"a\" type=\"primary\" disabled>Primary</Button>\n    <br />\n    <br />\n    <Button type=\"secondary\">Secondary</Button>&nbsp;&nbsp;\n    <Button type=\"secondary\" disabled>Secondary</Button>\n    <br />\n    <br />\n    <Button type=\"normal\">Normal</Button>&nbsp;&nbsp;\n    <Button type=\"normal\" disabled>Normal</Button>\n    <br />\n    <br />\n    <div>\n        <div className=\"ghost-light-background\">\n            <Button ghost=\"light\" disabled>Ghost Light</Button>\n        </div>\n        <div className=\"ghost-dark-background\">\n            <Button ghost=\"dark\" disabled>Ghost Dark</Button>\n        </div>\n    </div>\n</div>, mountNode);\n","css":".ghost-light-background {\n    display: inline-block;\n    height: 100px;\n    line-height: 100px;\n    width: 50%;\n    background: #EBECF0;\n    margin-bottom: 20px;\n    padding-left:10px;\n    box-sizing: border-box;\n}\n.ghost-dark-background {\n    display: inline-block;\n    height: 100px;\n    line-height: 100px;\n    width: 50%;\n    background: #333;\n    margin-bottom: 20px;\n    padding-left:10px;\n    box-sizing: border-box;\n}\n"},"body":"\n````jsx\nimport { Button } from '@alifd/next';\n\nReactDOM.render(<div>\n    <Button type=\"primary\">Primary</Button>&nbsp;&nbsp;\n    <Button component=\"a\" type=\"primary\" disabled>Primary</Button>\n    <br />\n    <br />\n    <Button type=\"secondary\">Secondary</Button>&nbsp;&nbsp;\n    <Button type=\"secondary\" disabled>Secondary</Button>\n    <br />\n    <br />\n    <Button type=\"normal\">Normal</Button>&nbsp;&nbsp;\n    <Button type=\"normal\" disabled>Normal</Button>\n    <br />\n    <br />\n    <div>\n        <div className=\"ghost-light-background\">\n            <Button ghost=\"light\" disabled>Ghost Light</Button>\n        </div>\n        <div className=\"ghost-dark-background\">\n            <Button ghost=\"dark\" disabled>Ghost Dark</Button>\n        </div>\n    </div>\n</div>, mountNode);\n````\n\n````css\n.ghost-light-background {\n    display: inline-block;\n    height: 100px;\n    line-height: 100px;\n    width: 50%;\n    background: #EBECF0;\n    margin-bottom: 20px;\n    padding-left:10px;\n    box-sizing: border-box;\n}\n.ghost-dark-background {\n    display: inline-block;\n    height: 100px;\n    line-height: 100px;\n    width: 50%;\n    background: #333;\n    margin-bottom: 20px;\n    padding-left:10px;\n    box-sizing: border-box;\n}\n````","html":"<script>(function(){\"use strict\";\n\nvar _next = require(\"@alifd/next\");\n\nReactDOM.render(React.createElement(\n    \"div\",\n    null,\n    React.createElement(\n        _next.Button,\n        { type: \"primary\" },\n        \"Primary\"\n    ),\n    \"\\xA0\\xA0\",\n    React.createElement(\n        _next.Button,\n        { component: \"a\", type: \"primary\", disabled: true },\n        \"Primary\"\n    ),\n    React.createElement(\"br\", null),\n    React.createElement(\"br\", null),\n    React.createElement(\n        _next.Button,\n        { type: \"secondary\" },\n        \"Secondary\"\n    ),\n    \"\\xA0\\xA0\",\n    React.createElement(\n        _next.Button,\n        { type: \"secondary\", disabled: true },\n        \"Secondary\"\n    ),\n    React.createElement(\"br\", null),\n    React.createElement(\"br\", null),\n    React.createElement(\n        _next.Button,\n        { type: \"normal\" },\n        \"Normal\"\n    ),\n    \"\\xA0\\xA0\",\n    React.createElement(\n        _next.Button,\n        { type: \"normal\", disabled: true },\n        \"Normal\"\n    ),\n    React.createElement(\"br\", null),\n    React.createElement(\"br\", null),\n    React.createElement(\n        \"div\",\n        null,\n        React.createElement(\n            \"div\",\n            { className: \"ghost-light-background\" },\n            React.createElement(\n                _next.Button,\n                { ghost: \"light\", disabled: true },\n                \"Ghost Light\"\n            )\n        ),\n        React.createElement(\n            \"div\",\n            { className: \"ghost-dark-background\" },\n            React.createElement(\n                _next.Button,\n                { ghost: \"dark\", disabled: true },\n                \"Ghost Dark\"\n            )\n        )\n    )\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Button <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Button</span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>primary<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Primary</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>Button</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">&amp;nbsp;&amp;nbsp;\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Button</span> <span class=\"token attr-name\">component</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>a<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>primary<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">disabled</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Primary</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>Button</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Button</span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>secondary<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Secondary</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>Button</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">&amp;nbsp;&amp;nbsp;\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Button</span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>secondary<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">disabled</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Secondary</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>Button</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Button</span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>normal<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Normal</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>Button</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">&amp;nbsp;&amp;nbsp;\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Button</span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>normal<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">disabled</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Normal</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>Button</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>ghost-light-background<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Button</span> <span class=\"token attr-name\">ghost</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>light<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">disabled</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Ghost Light</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>Button</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>ghost-dark-background<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Button</span> <span class=\"token attr-name\">ghost</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>dark<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">disabled</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Ghost Dark</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>Button</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div><style type=\"text/css\">.ghost-light-background {\n    display: inline-block;\n    height: 100px;\n    line-height: 100px;\n    width: 50%;\n    background: #EBECF0;\n    margin-bottom: 20px;\n    padding-left:10px;\n    box-sizing: border-box;\n}\n.ghost-dark-background {\n    display: inline-block;\n    height: 100px;\n    line-height: 100px;\n    width: 50%;\n    background: #333;\n    margin-bottom: 20px;\n    padding-left:10px;\n    box-sizing: border-box;\n}</style><div class=\"highlight\"><pre class=\"language-css\"><code class=\"language-css\"><span class=\"token selector\">.ghost-light-background</span> <span class=\"token punctuation\">{</span>\n    <span class=\"token property\">display</span><span class=\"token punctuation\">:</span> inline-block<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">height</span><span class=\"token punctuation\">:</span> 100px<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">line-height</span><span class=\"token punctuation\">:</span> 100px<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">width</span><span class=\"token punctuation\">:</span> 50%<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">background</span><span class=\"token punctuation\">:</span> #EBECF0<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">margin-bottom</span><span class=\"token punctuation\">:</span> 20px<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">padding-left</span><span class=\"token punctuation\">:</span>10px<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">box-sizing</span><span class=\"token punctuation\">:</span> border-box<span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span>\n<span class=\"token selector\">.ghost-dark-background</span> <span class=\"token punctuation\">{</span>\n    <span class=\"token property\">display</span><span class=\"token punctuation\">:</span> inline-block<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">height</span><span class=\"token punctuation\">:</span> 100px<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">line-height</span><span class=\"token punctuation\">:</span> 100px<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">width</span><span class=\"token punctuation\">:</span> 50%<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">background</span><span class=\"token punctuation\">:</span> #333<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">margin-bottom</span><span class=\"token punctuation\">:</span> 20px<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">padding-left</span><span class=\"token punctuation\">:</span>10px<span class=\"token punctuation\">;</span>\n    <span class=\"token property\">box-sizing</span><span class=\"token punctuation\">:</span> border-box<span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span></code></pre></div>"}