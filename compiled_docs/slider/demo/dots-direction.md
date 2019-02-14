{"title":"导航锚点方向","meta":{"title":"导航锚点方向","description":"\n<p>通过 <code>dotsDirection</code> 可以改变导航锚点的位置，默认为 <code>hoz</code> 即水平方向。\n当其值设为 <code>ver</code> 时为垂直方向展示。</p>\n","order":"4"},"codes":{"jsx":"import { Slider } from '@alifd/next';\n\nReactDOM.render(\n    <div>\n        <Slider dotsDirection=\"hoz\" arrows={false}>\n            <div><h3 className=\"h3\">1</h3></div>\n            <div><h3 className=\"h3\">2</h3></div>\n            <div><h3 className=\"h3\">3</h3></div>\n            <div><h3 className=\"h3\">4</h3></div>\n        </Slider>\n\n        <br />\n\n        <Slider dotsDirection=\"ver\" arrows={false}>\n            <div><h3 className=\"h3\">1</h3></div>\n            <div><h3 className=\"h3\">2</h3></div>\n            <div><h3 className=\"h3\">3</h3></div>\n            <div><h3 className=\"h3\">4</h3></div>\n        </Slider>\n    </div>\n    , mountNode);\n","css":".next-slick .h3, .h4 {\n        background: #4F74B3;\n        color: #fff;\n        line-height: 150px;\n        text-align: center;\n        margin-top: 0;\n        margin-bottom: 0;\n}\n\n.next-slick .h4 {\n        margin-right: 5px;\n        position: relative;\n}\n"},"body":"\n\n````jsx\nimport { Slider } from '@alifd/next';\n\nReactDOM.render(\n    <div>\n        <Slider dotsDirection=\"hoz\" arrows={false}>\n            <div><h3 className=\"h3\">1</h3></div>\n            <div><h3 className=\"h3\">2</h3></div>\n            <div><h3 className=\"h3\">3</h3></div>\n            <div><h3 className=\"h3\">4</h3></div>\n        </Slider>\n\n        <br />\n\n        <Slider dotsDirection=\"ver\" arrows={false}>\n            <div><h3 className=\"h3\">1</h3></div>\n            <div><h3 className=\"h3\">2</h3></div>\n            <div><h3 className=\"h3\">3</h3></div>\n            <div><h3 className=\"h3\">4</h3></div>\n        </Slider>\n    </div>\n    , mountNode);\n````\n\n````css\n.next-slick .h3, .h4 {\n        background: #4F74B3;\n        color: #fff;\n        line-height: 150px;\n        text-align: center;\n        margin-top: 0;\n        margin-bottom: 0;\n}\n\n.next-slick .h4 {\n        margin-right: 5px;\n        position: relative;\n}\n````","html":"<script>(function(){\"use strict\";\n\nvar _next = require(\"@alifd/next\");\n\nReactDOM.render(React.createElement(\n    \"div\",\n    null,\n    React.createElement(\n        _next.Slider,\n        { dotsDirection: \"hoz\", arrows: false },\n        React.createElement(\n            \"div\",\n            null,\n            React.createElement(\n                \"h3\",\n                { className: \"h3\" },\n                \"1\"\n            )\n        ),\n        React.createElement(\n            \"div\",\n            null,\n            React.createElement(\n                \"h3\",\n                { className: \"h3\" },\n                \"2\"\n            )\n        ),\n        React.createElement(\n            \"div\",\n            null,\n            React.createElement(\n                \"h3\",\n                { className: \"h3\" },\n                \"3\"\n            )\n        ),\n        React.createElement(\n            \"div\",\n            null,\n            React.createElement(\n                \"h3\",\n                { className: \"h3\" },\n                \"4\"\n            )\n        )\n    ),\n    React.createElement(\"br\", null),\n    React.createElement(\n        _next.Slider,\n        { dotsDirection: \"ver\", arrows: false },\n        React.createElement(\n            \"div\",\n            null,\n            React.createElement(\n                \"h3\",\n                { className: \"h3\" },\n                \"1\"\n            )\n        ),\n        React.createElement(\n            \"div\",\n            null,\n            React.createElement(\n                \"h3\",\n                { className: \"h3\" },\n                \"2\"\n            )\n        ),\n        React.createElement(\n            \"div\",\n            null,\n            React.createElement(\n                \"h3\",\n                { className: \"h3\" },\n                \"3\"\n            )\n        ),\n        React.createElement(\n            \"div\",\n            null,\n            React.createElement(\n                \"h3\",\n                { className: \"h3\" },\n                \"4\"\n            )\n        )\n    )\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Slider <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span>\n    <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Slider</span> <span class=\"token attr-name\">dotsDirection</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>hoz<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">arrows</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token boolean\">false</span><span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>h3</span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>h3<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">1</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>h3</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>h3</span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>h3<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">2</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>h3</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>h3</span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>h3<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">3</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>h3</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>h3</span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>h3<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">4</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>h3</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>Slider</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Slider</span> <span class=\"token attr-name\">dotsDirection</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>ver<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">arrows</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token boolean\">false</span><span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>h3</span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>h3<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">1</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>h3</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>h3</span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>h3<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">2</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>h3</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>h3</span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>h3<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">3</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>h3</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n            </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>h3</span> <span class=\"token attr-name\">className</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>h3<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">4</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>h3</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>Slider</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span>\n    <span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div><style type=\"text/css\">.next-slick .h3, .h4 {\n        background: #4F74B3;\n        color: #fff;\n        line-height: 150px;\n        text-align: center;\n        margin-top: 0;\n        margin-bottom: 0;\n}\n\n.next-slick .h4 {\n        margin-right: 5px;\n        position: relative;\n}</style><div class=\"highlight\"><pre class=\"language-css\"><code class=\"language-css\"><span class=\"token selector\">.next-slick .h3, .h4</span> <span class=\"token punctuation\">{</span>\n        <span class=\"token property\">background</span><span class=\"token punctuation\">:</span> #4F74B3<span class=\"token punctuation\">;</span>\n        <span class=\"token property\">color</span><span class=\"token punctuation\">:</span> #fff<span class=\"token punctuation\">;</span>\n        <span class=\"token property\">line-height</span><span class=\"token punctuation\">:</span> 150px<span class=\"token punctuation\">;</span>\n        <span class=\"token property\">text-align</span><span class=\"token punctuation\">:</span> center<span class=\"token punctuation\">;</span>\n        <span class=\"token property\">margin-top</span><span class=\"token punctuation\">:</span> 0<span class=\"token punctuation\">;</span>\n        <span class=\"token property\">margin-bottom</span><span class=\"token punctuation\">:</span> 0<span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span>\n\n<span class=\"token selector\">.next-slick .h4</span> <span class=\"token punctuation\">{</span>\n        <span class=\"token property\">margin-right</span><span class=\"token punctuation\">:</span> 5px<span class=\"token punctuation\">;</span>\n        <span class=\"token property\">position</span><span class=\"token punctuation\">:</span> relative<span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span></code></pre></div>"}