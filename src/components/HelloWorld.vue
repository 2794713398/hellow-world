<template>
  <div class="hello">
    <h1>注册界面</h1>
    <h3>青春不常在，抓紧谈恋爱</h3>
    <table width="600" bgcolor="pink">
        <tr>
            <td> <label for="usename">姓名：</label></td>
            <td> <input type="text" name="user" value="请输入姓名：" maxlength="9" id="usename"/></td>
        </tr>
    
    
    <tr>
            <td>性别：</td>
            <td>
                <input type="radio" name="name1" value="男" id="M"/><label for="M"> <img src="../../image/墨尔本1.jpg" width="20">男</label> 
                <input type="radio" name="name1" value="女" id="m"/><label for="m"><img src="../../image/墨尔本2.jpg" width="20">女</label>
                <input type="radio" name="name1" value="人妖" checked="checked" id="g" /> <label for="g" class="blue"><img src="../../image/墨尔本3.jpg" width="20">人妖</label> 
            </td>
        </tr>

        <tr>
            <td>生日：</td>
            <td>
                <select>
                    <option>--请选择年份--</option>
                    <option>2000</option> 
                    <option>2001</option>
                    <option>2001</option>
                </select>
                <select>
                    <option>--请选择月份--</option>
                    <option>1</option> 
                    <option>2</option>
                    <option>3</option>
                </select>
                <select>
                    <option>--请选择天份--</option>
                    <option>1</option> 
                    <option>2</option>
                    <option>3</option>
                </select>
            </td>
        </tr>

        <tr>
            <td>所在地区：</td>
            <td><input type="text" value="火星"></td>
        </tr>

        <tr>
            <td>婚姻状况：</td>
            <td>
                <input type="radio" name="name2" value="未婚" id="jiehun" checked="checked"/> <label for="jiehun">未婚</label> 
                <input type="radio" name="name2" value="已婚" id="yihun"/><label for="yihun">已婚</label>
                <input type="radio" name="name2" value="离异"  id="liyi"/> <label for="liyi">离异</label>
            </td>
        </tr>

        <tr>
            <td>学历情况：</td>
            <td><input type="text" value="幼儿园毕业"></td>
        </tr>

        <tr>
            <td>喜欢的类型：</td>
            <td>
                <input type="checkbox" name="love" >可爱的
                <input type="checkbox" name="love" >好看的
                <input type="checkbox" name="love" >知性的
                <input type="checkbox" name="love" >成熟的
                <input type="checkbox" name="love" checked="checked">都喜欢
            </td>
        </tr>

        <tr>
            <td>自我介绍：</td>
            <td><textarea cols="50" rows="3"> 写在这里，对!
            </textarea><br></td>
        </tr>

        <tr>
            <td></td>
            <td><input type="submit" value="免费注册" /></td>
        </tr>

        <tr>
            <td></td>
            <td><input type="checkbox"  checked="checked"  />我同意注册条款</td>
        </tr>

        <tr>
            <td></td>
            <td><a href="#">我是会员登录</a></td>
        </tr>

        <tr>
            <td></td>
            <td>
                <h5>我承诺：</h5>
                <ul>
                    <li class="blue">我说的都是真的</li>
                    <li class="aqua">本人已经成年</li>
                    <li>我是正常人</li>
                </ul>
            </td>
        </tr>

        
      </table>
      <table align="center" border="1" cellpadding="20" cellspacing="0" width="500" height="250">
    <thead>
        <tr>
          <th>排行</th> 
          <th>作品名字</th> 
          <th>趋势</th> 
          <th>月票</th> 
          <th>相关链接</th></tr>
    </thead>
    <tbody>
        <tr>
          <td>1</td> 
          <td>光阴之外</td> 
          <td><img src="../../image2/up.jpg" width="20"></td> 
          <td>12223</td> 
          <td><a href="https://book.qidian.com/info/1031777108/" target="_blank"><img src="../../image2/光阴之外.png" width="30"></a></td>
        </tr>

        <tr>
          <td>2</td>
          <td>灵境行者</td> 
          <td><img src="../../image2/up.jpg" width="20"></td> 
          <td>11353</td> 
          <td><a href="https://book.qidian.com/info/1031940621/" target="_blank"><img src="../../image2/灵境行者.png" width="30"></a></td>
        </tr>

        <tr>
          <td>3</td> 
          <td>深空彼岸</td> 
          <td><img src="../../image2/down.png" width="20"></td> 
          <td>7198</td> 
          <td><a href="https://book.qidian.com/info/1027339371/" target="_blank"><img src="../../image2/深空彼岸.png" width="30"></a></td>
        </tr>
    </tbody>
    </table>
    <iframe src="https://www.bilibili.com/" width="600" height="300" frameborder="0"></iframe>

        <div class=" box red">红色</div>
        <div class="box green">绿色</div>
        <div class="box" id="yellow">黄色</div>
      
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* 选择器{样式} */
        /* 给谁改样式{改什么样式} */
        /* 标签选择器 */
        /* #id选择器，只能用一次 */
        /* *通识符选择器，一旦设定所有标签自动调用 */
        h3 {
            color: brown;
            font-size: 20px; 
            /* px像素大小的意思 */
        }
        /* 类选择器 */
        .box {
            width: 100px;
            height: 100px;
        }
        .blue {
            color: blue;
        }
        .aqua {
            color: aqua;
        }
        .red {
            /* 背景颜色 */
            background-color: red;
        }
        .green {
            /* 背景颜色 */
            background-color: green;
        }
        #yellow {
            background-color: yellow;
        }
        h3 {
            font-family: '宋体';
        }
        /* 标题文字比较特殊需要指定大小单独 */
        /* 字体设置顺序font style weight size famliy */
        body {
            font-size: 18px;
        }
        h3 {
            /* 本质是让h3盒子里的文字居中对齐 */
            text-align: center;
            /* text-indent:文本首行缩进 */
        }

        table
        { 
          margin-right: auto;
          margin-left: auto;
        }

</style>
