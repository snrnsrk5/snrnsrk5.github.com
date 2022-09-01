---
layout: post
title: "string 회전출력 문제"
date: 2022-09-01
excerpt: "자료구조 03"
tags: [cpp, string]
comments: true
---
```cpp
#include <iostream>
#include <vector>
#include <string>
using namespace std;

int main() {
	string len;
	string cen;

	cout << "빈칸을 포함하는 문자열을 입력하시오." << endl;

	getline(cin, len);

	int leni = len.length() - 1;

	for (int i = 0; i < leni; i++)
	{
		cen.push_back(len.front());
		len.erase(0, 1);

		cout << len << cen << endl;
	}
}
```