# ${1}

<div id="top"></div>

## Table of Contents 

1. [about](#about)
2. [directory construction](#directory construction)
3. [environment](#environment)
4. [how to print](#how to print)
5. [trouble shooting](#trouble shooting)

# about

D2ロボコン用の寿司テーブルです。

<p align="right">(<a href="#top">Back to the top</a>)</p>

## directory construction

print

<!-- use tree command -->


<p align="right">(<a href="#top">Back to the top</a>)</p>

## environment


## how to print
作成は3Dプリンタとレーザーカッターを使用します。  
プリントデータはすべてprintディレクトリに入っています。  
各モジュールに必要なプリントは以下の通りです。  

### 最小モジュール構成数
curve_module : 8個
linear_module : 2個
power_module : 1個  

### 3dプリンタパーツ　　
SUSHIディレクトリの中にあるgcode.3mfファイルすべて(SHSHI_rail_A1, SUSHI_rail_mini はそれぞれ2回ずつ)
### curve_module
- curve_module\back_under : レーザー5.5mm
- curve_module\back_upper : レーザー5.5mm
- curve_module\front : レーザー5.5mm
- curve_module\base : レーザー2.5mm
- curve_module\rail_base : レーザー2.5mm
- curve_module\base : レーザー2.5mm 2枚
### linear_module
- linear_module\back_under : レーザー5.5mm
- linear_module\back_upper : レーザー5.5mm
- linear_module\front : レーザー5.5mm
- linear_module\base : レーザー2.5mm
- linear_module\rail_base : レーザー2.5mm
- linear_module\base : レーザー2.5mm 2枚
### power_module
- power_module_gears\M3_15 : レーザー5.5mm
- power_module_gears\M3_15_input : レーザー5.5mm
- power_module_gears\M3_38 : レーザー5.5mm 2枚
- power_module_gears\roller : レーザー5.5mm

- power_module_motor\gear_plate_cover : レーザー5.5mm
- power_module_motor\motor_setter_fixer : レーザー5.5mm
- power_module_motor\motor_setter_front : レーザー5.5mm
- power_module_motor\motor_setter_middle : レーザー5.5mm

- power_module_plate\connector : レーザー2.5mm 3枚
- power_module_plate\gear_plate_1 : レーザー5.5mm
- power_module_plate\gear_plate_2 : レーザー5.5mm, レーザー2.5mm
- power_module_plate\gear_plate_3 : レーザー5.5mm
- power_module_plate\gear_plate_base : レーザー2.5mm
- power_module_plate\stopper : レーザー2.5mm

### 皿
- ./dish_print : レーザー2.5mm 17セット


<p align="right">(<a href="#top">Back to the top</a>)</p>

## trouble shooting


<p align="right">(<a href=\"#top\">Back to the top</a>)</p>