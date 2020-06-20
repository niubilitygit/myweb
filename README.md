# myweb
#字典的创建与输出
'''
car_0 = {'color': 'white' ,'price': '20w'}
print(car_0['color'])
print(car_0['price'])
'''

#字典元素的添加
'''car_0 = {'name' : 'adui' , 'color' : 'green'}
print(car_0)
car_0['price'] = 47
car_0['sudu'] = 280
print(car_0)
#修改字典元素值
car_0['price'] = 89
car_0['color'] = 'black'
print(car_0)
#删除字典元素
del car_0['sudu']
print(car_0)
'''

#外星人位置的追踪
alien_0 = {'type':'frist','color' : 'yellow' , 'haemal strand':'3'}
print(alien_0)

#插入外星人的位置
alien_0['x_position'] = 25
alien_0['y_position'] = 0
print(alien_0)

#根据外星人类型来向右移动
if alien_0['type'] == 'frist':
    x_increase = 1
elif alien_0['type'] == 'second':
    x_increase = 2
else:
    x_increase = 3
alien_0['x_position'] = alien_0['x_position'] + x_increase
print('The alien x_position is ' + str(alien_0['x_position'])+'!')










