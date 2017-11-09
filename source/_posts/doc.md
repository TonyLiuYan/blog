---
layout: this
title: doc
date: 2017-11-08 22:51:29
tags:
---

测试这是新添加的


分地方得分东风反对反对反对


```csharp
class Program
{

	static void Main(string[] args)
	{
		string msg = string.Empty;
		f1("haha", out msg);
		string s = msg;
	}

	static string f1(string p1, out string msg)
	{
		msg = string.Empty;
		if (p1 == "haha")
		{
			if (p1 != null)
				f2(p1, out msg);
			if (!string.IsNullOrEmpty(msg))
			{
				return null;
			}
		}
		msg = "error";
		return null;
	}

	static string f2(string p1, out string o1)
	{
		if (p1 == "haha")
		{
			o1 = "bingo";
			return "bingo";
		}
		o1 = "error";
		return null;
	}


}
```