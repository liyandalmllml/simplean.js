<<<<<<< HEAD
#Simplean.js
*language: [中文](README.zh-cn.md)*

  * Focus on dom animation 
  * Focus on mobile browser and advanced browser
  * Simple api: to, addClass, removeClass

## Usage
````
    .rect-200 {
        width: 200px;
        height: 200px;
    }

    Simplean(dom).addClass('rect-200', {
        duration: 500,
        delay: 100,
        onStart: function () {
            // do something
        },
        onStop: function () {
            // do something
        }
    });
````
## API

### Simplean#to(styles[, options])
````
    Simplean(dom).to({
        width: 200px;
        background-color: red;
    });
````
````
    Simplean(dom).to({
        height: 200px;
        border-radius: 50px;
    }, {
        ease: 'ease-out'
    });
````
### Simplean#addClass(classNames[, options])
````
    .highlight {
        color: red;
        background: blue;
    }

    Simplean(dom).addClass('highlight', {
        ease: 'ease-in-out',
        onStart: function () {
            console.log('I will be highlight');
        },
        onStop: function () {
            console.log('I\'m be highlight');
        }
    });
````

### Simplean#removeClass(classNames[, options])
````
    .rotate-30 {
        transform: rotate(30deg)
    }

    Simplean(dom).removeClass('rotate-30', {
        ease: 'ease-in',
    });
````

## OPTIONS

 All api in Simplean.js has a argument that is options which make the process of animation controable. Options is a object has six properties: delay, duration, ease, deep, onStart, onStop. 
 * `delay` - Delay means animation wait some time for starting.The default value is 0ms.
 * `duration` - Duration means animation running time.The default value is 300ms.
 * `ease` - Ease means animation timing function.In simple term, timing function is a function that caculate the instant status as time passing.The default is linear.
 * `deep` - For addClass and removeClass
 * `onStart` - The function invoked before animation starting.
 * `onStop` - The function invoked after animation stopping.
 
=======
#Simplean.js
*language：[English](README.en-us.md)*
* 专注于移动端与高级浏览器
* 专注于DOM动画
* 专注于简单的特性，只提供三个API：to、addClass、removeClass

## 目录
- [快速开始](#quickStart)
- [所有API](#allApi)
- [BUG](#bug)
- [联系我们](#author)

<a name="quickStart"></a>
## 快速开始
<a name="allApi"></a>
## 所有API
<a name="bug"></a>
## BUG
<a name="author"></a>
## 联系我们
>>>>>>> add two version
