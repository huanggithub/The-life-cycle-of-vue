# The-life-cycle-of-vue
## vue学习篇之--生命周期钩子
    beforeCreate  //创建前
    created       //创建后
    beforeMount   //挂载前
    mounted       //挂载结束
    beforeUpdate  //更新前
    updated       //更新完成
    beforeDestroy //销毁前
    destroyed     //销毁后
## 生命周期钩子函数使用
    beforecreate : 举个栗子：可以在这加个loading事件 
    created ：在这结束loading，还做一些初始化，实现函数自执行 
    mounted ： 在这发起后端请求，拿回数据，配合路由钩子做一些事情
    beforeDestory： 你确认删除XX吗？ 
    destoryed ：当前组件已被删除，清空相关内容
