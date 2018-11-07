uts "Por favor digite seu nome usuário"
nome = gets.chomp
puts "Seja Bem Vindo #{nome} à calculadora de matrizes 3x3"
puts
puts "Por gentileza digite os valores da matriz"
puts
puts "Sendo os valores contados da esquerda para à direita na primeira linha e depois nas consequentes"
puts
puts "Primeiro valor"
val1 = gets.chomp.to_i
puts "Segundo  valor"
val2 = gets.chomp.to_i
puts "Terceiro valor"
val3 = gets.chomp.to_i
puts "Quarto valor"
val4 = gets.chomp.to_i
puts "Quinto valor"
val5 = gets.chomp.to_i
puts "Sexto valor"
val6 = gets.chomp.to_i
puts "Sétimo valor"
val7 = gets.chomp.to_i
puts "Oitavo valor"
val8 = gets.chomp.to_i
puts "Nono valor"
val9 = gets.chomp.to_i
puts "A sua matriz ficará assim :" 
puts "#{val1}  |#{val2}|   #{val3}|"
puts "#{val4}  |#{val5}|   #{val6}|"	                              
puts "#{val7}  |#{val8}|   #{val9}|"

puts "Deseja fazer alguma operação com essa matriz?"
puts "Digite a opção"
puts "1- Adição"
puts "2- Subtração"
puts "3- Multiplicação"
opcao = gets.chomp.to_i

case opcao
	when 1 
		puts"Digite os valores da segunda matriz"
		puts "Primeiro valor"
		val10 = gets.chomp.to_i
		puts "Segundo  valor"
		val11 = gets.chomp.to_i
		puts "Terceiro valor"
		val12 = gets.chomp.to_i
		puts "Quarto valor"
		val13 = gets.chomp.to_i
		puts "Quinto valor"
		val14 = gets.chomp.to_i
		puts "Sexto valor"
		val15 = gets.chomp.to_i
		puts "Sétimo valor"
		val16= gets.chomp.to_i
		puts "Oitavo valor"
		val17 = gets.chomp.to_i
		puts "Nono valor"
		val18 = gets.chomp.to_i
		puts "A sesgunda matriz ficará assim :" 
		puts "#{val10}  |#{val11}|   #{val12}|"
		puts "#{val13}  |#{val14}|   #{val15}|"	                              
		puts "#{val16}  |#{val17}|   #{val18}|"

		val19 =val1 + val10
		val20 =val2 + val11
		val21 =val3 + val12
		val22 =val4 + val13
		val23 =val5 + val14
		val24 =val6 + val15
		val25 =val7 + val16
		val26 =val8 + val17
		val27 =val9 + val18


		puts"A soma das matrizes será:"
		puts "#{val19}  |#{val20}|   #{val21}|"
		puts "#{val22}  |#{val23}|   #{val24}|"	                              
		puts "#{val25}  |#{val26}|   #{val27}|"

	when 2
		puts"Digite os valores da segunda matriz"
		puts "Primeiro valor"
		val10 = gets.chomp.to_i
		puts "Segundo  valor"
		val11 = gets.chomp.to_i
		puts "Terceiro valor"
		val12 = gets.chomp.to_i
		puts "Quarto valor"
		val13 = gets.chomp.to_i
		puts "Quinto valor"
		val14 = gets.chomp.to_i
		puts "Sexto valor"
		val15 = gets.chomp.to_i
		puts "Sétimo valor"
		val16= gets.chomp.to_i
		puts "Oitavo valor"
		val17 = gets.chomp.to_i
		puts "Nono valor"
		val18 = gets.chomp.to_i
		puts "A segunda matriz ficará assim :" 
		puts "#{val10}  |#{val11}|   #{val12}|"
		puts "#{val13}  |#{val14}|   #{val15}|"	                              
		puts "#{val16}  |#{val17}|   #{val18}|"

		val19 =val1 - val10
		val20 =val2 - val11
		val21 =val3 - val12
		val22 =val4 - val13
		val23 =val5 - val14
		val24 =val6 - val15
		val25 =val7 - val16
		val26 =val8 - val17
		val27 =val9 - val18


		puts"A subtração das matrizes será:"
		puts "#{val19}  |#{val20}|   #{val21}|"
		puts "#{val22}  |#{val23}|   #{val24}|"	                              
		puts "#{val25}  |#{val26}|   #{val27}|"

when 3
		puts"Digite os valores da segunda matriz"
		puts "Primeiro valor"
		val10 = gets.chomp.to_i
		puts "Segundo  valor"
		val11 = gets.chomp.to_i
		puts "Terceiro valor"
		val12 = gets.chomp.to_i
		puts "Quarto valor"
		val13 = gets.chomp.to_i
		puts "Quinto valor"
		val14 = gets.chomp.to_i
		puts "Sexto valor"
		val15 = gets.chomp.to_i
		puts "Sétimo valor"
		val16= gets.chomp.to_i
		puts "Oitavo valor"
		val17 = gets.chomp.to_i
		puts "Nono valor"
		val18 = gets.chomp.to_i
		puts "A segunda matriz ficará assim :" 
		puts "#{val10}  |#{val11}|   #{val12}|"
		puts "#{val13}  |#{val14}|   #{val15}|"	                              
		puts "#{val16}  |#{val17}|   #{val18}|"

		val19 =(val1 * val10) + (val2 * val13) + (val3 * val16)
		val20 =(val1 * val11) + (val2 * val14) + (val3 * val17)
		val21 =(val1 * val12) + (val2 * val15) + (val3 * val18)
		val22 =(val4 * val10) + (val5 * val13) + (val6 * val16)
		val23 =(val4 * val11) + (val5 * val14) + (val6 * val17)
		val24 =(val4 * val12) + (val5 * val15) + (val6 * val18)
		val25 =(val7 * val10) + (val8 * val13) + (val9 * val16)
		val26 =(val7 * val11) + (val8 * val14) + (val9 * val17)
		val27 =(val7 * val12) + (val8 * val15) + (val9 * val18)


		puts"A multiplicação das matrizes será:"
		puts "#{val19}  |#{val20}|   #{val21}|"
		puts "#{val22}  |#{val23}|   #{val24}|"	                              
		puts "#{val25}  |#{val26}|   #{val27}|"
end

		num1 = gets.chomp.to_i
		puts "Por favor agora digite o segundo valor da divisão"
		num2 = gets.chomp.to_i
		div =num1 / num2
		puts "Sendo assim #{nome} a divisão de #{num1} com o #{num2} é exatamente #{div}"
		puts
		puts
		puts
		puts"Alguma outra operação?"
		puts
		end
	end
end
