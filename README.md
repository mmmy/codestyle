###React项目结构参考
- src/
    - index.html
    - main.js 
    - components/
        - XXX/
        - XXX/
        - XXX/
        - util/
        - tpl/
        - widgets/
    - stores/
    - actions/
    - backend/
    - styles/
        - main.less
        - varibale.less
        - mixin.less
        - component/ 
    - resourse/
        - font/
        - image/

###React View Template问题
参考 https://github.com/airbnb/javascript/tree/master/react
个人总结这样层次比较好:

- stateless模板,即纯组件(不依赖store,作为另一个组件的子组件) & 组件中不含stata或者refs 
   ```
    // good
    function Listing({ hello }) {
        return <div>{hello}</div>;
    }
   ```
    