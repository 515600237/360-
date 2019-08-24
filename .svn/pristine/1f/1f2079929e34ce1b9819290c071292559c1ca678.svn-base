import Vue from 'vue'
import Router from 'vue-router'
/*import Assess from '@/components/Assess'*/
import Answer from "@/components/components/Answer"

Vue.use(Router)

export default new Router({
  routes: [
    {
      path: "/",
      redirect: "/AssessContent"
    },
    {
      path: '/AssessContent',
      name: 'AssessContent',
      component: resolve=>require(['@/components/components/AssessContent'],resolve)
    },
    {
      path:"/Answer",
      name:"Answer",
      component: resolve=>require(['@/components/components/Answer'],resolve)
    },
  ]
})
