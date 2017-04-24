
## H5 input输入类型

  1.Input 类型 - email
  email 类型用于应该包含 e-mail 地址的输入域。
  在提交表单时，会自动验证 email 域的值。
  
  2.Input 类型 - url
  url 类型用于应该包含 URL 地址的输入域。
  在提交表单时，会自动验证 url 域的值。
  
  3.Input 类型 - number
  number 类型用于应该包含数值的输入域。
  您还能够设定对所接受的数字的限定：min(最小值) max(最大值)
  
  4.Input 类型 - range
  range 类型用于应该包含一定范围内数字值的输入域。
  range 类型显示为滑动条。
  您还能够设定对所接受的数字的限定：min(最小值) max(最大值)
  
  5.Input 类型 - Date Pickers（日期选择器）
  HTML5 拥有多个可供选取日期和时间的新输入类型：
  date - 选取日、月、年
  month - 选取月、年
  week - 选取周和年
  time - 选取时间（小时和分钟）
  datetime - 选取时间、日、月、年（UTC 时间）
  datetime-local - 选取时间、日、月、年（本地时间）
  您从日历中选取一个日期：
  
  6.Input 类型 - search
  search 类型用于搜索域，比如站点搜索或 Google 搜索。
  search 域显示为常规的文本域。

## H5 input元素类型
```HTML
  1.datalist 元素
  datalist 元素规定输入域的选项列表。
  列表是通过 datalist 内的 option 元素创建的。
  
  2.keygen 元素
  keygen 元素的作用是提供一种验证用户的可靠方法。
  keygen 元素是密钥对生成器（key-pair generator）。当提交表单时，会生成两个键，一个是私钥，一个公钥。
  私钥（private key）存储于客户端，公钥（public key）则被发送到服务器。公钥可用于之后验证用户的客户
  端证书（client certificate）。
  
  3.output 元素
  output 元素用于不同类型的输出，比如计算或脚本输出：
```  
  
## H5 表单属性
```HTML
  1.autocomplete 属性
  autocomplete 属性规定 form 或 input 域应该拥有自动完成功能。
  注释：autocomplete 适用于 <form> 标签，以及以下类型的 <input> 标签：text, search, url, telephone,
  email,password, datepickers, range 以及 color。
  
  2.autofocus 属性
  autofocus 属性规定在页面加载时，域自动地获得焦点。
  注释：autofocus 属性适用于所有 <input> 标签的类型。
  
  3.form 属性
  form 属性规定输入域所属的一个或多个表单。
  注释：form 属性适用于所有 <input> 标签的类型。
  form 属性必须引用所属表单的 id：
  
  4.表单重写属性
  表单重写属性（form override attributes）允许您重写 form 元素的某些属性设定。
  表单重写属性有：
  formaction - 重写表单的 action 属性
  formenctype - 重写表单的 enctype 属性
  formmethod - 重写表单的 method 属性
  formnovalidate - 重写表单的 novalidate 属性
  formtarget - 重写表单的 target 属性
  注释：表单重写属性适用于以下类型的 <input> 标签：submit 和 image。
  
  5.height 和 width 属性
  height 和 width 属性规定用于 image 类型的 input 标签的图像高度和宽度。
  注释：height 和 width 属性只适用于 image 类型的 <input> 标签。
  
  6.list 属性
  list 属性规定输入域的 datalist。datalist 是输入域的选项列表。
  注释：list 属性适用于以下类型的 <input> 标签：text, search, url, telephone, email, date pickers,
  number,range 以及 color。
  
  7.min、max 和 step 属性
  min、max 和 step 属性用于为包含数字或日期的 input 类型规定限定（约束）。
  max 属性规定输入域所允许的最大值。
  min 属性规定输入域所允许的最小值。
  step 属性为输入域规定合法的数字间隔（如果 step="3"，则合法的数是 -3,0,3,6 等）。
  注释：min、max 和 step 属性适用于以下类型的 <input> 标签：date pickers、number 以及 range。
  下面的例子显示一个数字域，该域接受介于 0 到 10 之间的值，且步进为 3（即合法的值为 0、3、6 和 9）：
  
  8.multiple 属性
  multiple 属性规定输入域中可选择多个值。
  注释：multiple 属性适用于以下类型的 <input> 标签：email 和 file。
  
  9.novalidate 属性
  novalidate 属性规定在提交表单时不应该验证 form 或 input 域。
  注释：novalidate 属性适用于 <form> 以及以下类型的 <input> 标签：text, search, url, telephone, 
  email,password, date pickers, range 以及 color.
  
  10.pattern 属性
  pattern 属性规定用于验证 input 域的模式（pattern）。
  模式（pattern） 是正则表达式。您可以在我们的 JavaScript 教程中学习到有关正则表达式的内容。
  注释：pattern 属性适用于以下类型的 <input> 标签：text, search, url, telephone, email 以及 password。
  
  11.placeholder 属性
  placeholder 属性提供一种提示（hint），描述输入域所期待的值。
  注释：placeholder 属性适用于以下类型的 <input> 标签：text, search, url, telephone, email 以及 password。
  
  12.required 属性
  required 属性规定必须在提交之前填写输入域（不能为空）。
  注释：required 属性适用于以下类型的 <input> 标签：text, search, url, telephone, email, password, date           pickers, number, checkbox, radio 以及 file。
```
### 以上是W3C对于表单一些新特性的概述。
