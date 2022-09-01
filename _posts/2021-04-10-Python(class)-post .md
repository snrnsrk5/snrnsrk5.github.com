---
layout: post
title: "Python"
date: 2020-03-29
excerpt: "class"
tags: [sample post, readability, test]
comments: true
---
# py-class

    x, y = input("기본 x, y 값을 입력하세요 : ").split()
    xm, ym = input("이동할 x, y 값을 입력하세요 : ").split()
    class  point():
		def  __init__(self, x, y):
		    self.x = x
		    self.y = y
	    def  set(self, x, y):
		    self.x = x
		    self.y = y
	    def  get(self):
		    return (self.x, self.y)
	    def  move(self, xm, ym):
		    self.x = self.x + xm
		    self.x = self.x + xm
	xy = point(x, y)
	xy.set(int(x), int(y))
	xy.move(int(xm), int(ym))
	xym = (xy.get())
	print("x = ", xym[0], "\ny = ", xym[1])
    

