# 3_24
#1
letters="python"
print(f"letters:{letters}\n")
print(f"letters[0]:{letters[0]}")
print(f"letters[2]:{letters[2]}")

#2
string = 'PYTHON'
s_reverse = ''  
for char in string:
    s_reverse = char + s_reverse

print(s_reverse)  

#3
url="http://sharebook.kr"
print(f"url:{url}\n")

print("1. str.rfind('찾을문자')")
domain=url.rfind('.',0,1)

print(f"url.rfind('.'):{domain}")

#4
file_name='보고서.xlsx'
if file_name.endswith('.xlsx'):
    print('It dose not starts with .xlsx')
print(file_name.endswith('.xlsx'))

#5
file_name='2020_보고서.xlsx'

if file_name.startswith('2020'):
    print('It start with 2020')
print(file_name.startswith('2020'))



#6
score=int(input('점수를 입력하세요:'))
if score>=81:
     g='A'
elif score>=61:
     g='B'
elif score>=41:
     g='C'
elif score>=21:
    g='D'
else:
     g='E'
print('학점: %s' % g)




#7
cook=["피자","김밥","만두","양념치킨","족발","피자","김치만두","쫄면","소시지","라면","팥빙수","김치전"]
print(len(cook))

#8
warn_investment_list = ["Microsoft", "Google", "Naver", "Kakao", "SAMSUNG", "LG"]
a = input("투자종목을 입력해주세요 : ")
if a in warn_investment_list:
    print("투자 경고 종목입니다.")
else:
    print("투자 경고 종목이 아닙니다.")

#9
list=[100,200,300]
for i in list:
    print(i+10)
# 10
list=["sk하이닉스","삼성전자","LG전자"]
for i in list:
    print(len(i))
