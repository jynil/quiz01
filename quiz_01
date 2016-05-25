(1)請說明 Fixnum (整數) 和 Float (浮點數) 之間的差異
Fixnum 指的是任何整數
Float 指的是帶有小數點的物件 


(2)puts str1 + str2 / puts "#{str1}#{str2}" 之不同 #

puts "#{str1}#{str2}" => 可以使用在 "內插" 的情境…比如 puts "i am going to #{str1}" 時使用
puts str1+str2 只能單純顯示


(3)請解釋 array 和 hash 的不同處
array -> 是一種陣列元素，可以放任何的類別，用數字做為key
hash -> 是一種 key-value的資料結構，可以用任何物件做為 key


(4)請寫一段 code 從 [1, "a string", 3.14, [1,2,3,4]] 這個陣列找出所有非字串的值
a = [1, "a string", 3.14, [1,2,3,4]]
a.all? {|x| x.is_a? string}


i=0
array=[1, "hello", 2, 3, [1,2,3], "cool", 9, 10]

while (i<array.length)
	if(!(array[i].is_a? String))
		puts "#{array[i]}"
	end
i+=1
end

(5)請列出兩種產出亂數的方法
rand()
suffle

(6)請把 hoemowrk1 程式碼裡的裡面的使用者輸入兩個數字的方式和輸贏的判斷式改寫成 method


(7)以下這段程式碼：

((1 > 3)&&(true == true))||(!!!false)
會執行出什麼結果？ 請試試不用 irb 算出結果

第一步判斷 1>3 為 false
(1>3)&&(true==ture) 因&&左邊為false，所以無需管 true==true
第二步
false||(!!!false)
||的左邊為 false，則要判斷右邊的算式。 !!!false 為 true
因此 整個算式的結果為 true



(8)請問 binding.pry 是什麼？ 要如何使用它？
Runtime invocation。也就是可以在執行時攔截呼叫。把binding.pry埋在rails的程式中，在執行 rails s的時侯可以跳出 console，協助開發者debug。



(9)下面的一段程式碼，請嘗試用其他方法把 if...else...end 簡化成一行

var = 5

if var >= 5
  return "var is greater than or equal to 5"
else
  return "var is less than 5"
end

var = 5
puts ( Vat >= 5 ? "var is greater than or equal to 5" : "vat is less than 5" )


