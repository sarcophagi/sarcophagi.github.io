---
layout: post
title: scipy优化
categories: scipy
description: 优化函数
keywords: 优化函数, python
---

*最小化多元标量函数


'''
scipy.optimize.minize(fun,x0,args=0,method=None,jac=None,hess=None,bounds=None,constraints=(),tol=None,callback=None,options=None)
'''

fun：目标函数。
x0：初始迭代点。

method：求解方法。