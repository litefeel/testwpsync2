---
ID: 104
post_title: 中文名字1
post_name: 中文名字2
post_date: 2017-08-12 09:48:29
layout: post
link: >
  https://wp.litefeel.com/blog/2017/08/12/testtaaaaa1/
published: true
tags: [ ]
categories:
  - Uncategorized
---
testetesttss
aaabbb
sss
sadsafdsafdsa
a
a

# HEAD1

~~~ csharp
this is code
this is code
~~~

[litefeel](https://www.litefeel.com)


<https://www.litefeel.com>



~~~ csharp
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class AutoRemoveAnimation: MonoBehaviour {

    private Animator animator;
	
	void Start () {
        animator = GetComponentInChildren<Animator>();
	}
	
	void Update () {
		if (animator != null)
        {
            if (animator.GetCurrentAnimatorStateInfo(0).normalizedTime >= 1.0f)
            {
#if UNITY_EDITOR
                GameObject.DestroyImmediate(gameObject);
#else
                GameObject.Destroy(gameObject);
#endif
            }
        }
	}
}
~~~

