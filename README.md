# Estudo_de_Ruby
Apenas colocando meus projetos de estudo em Ruby

#ola_mundo

puts"Olá mundo"

#menu_num_inteiro 

puts"informe três numeros"
a=gets.chomp.to_i 
b=gets.chomp.to_i 
c=gets.chomp.to_i

puts"Escolha uma opção 1 - Conferir o maior numero \n 2- Conferir o menor numero \n 3- Produto \n 4 - Media"
escolha = gets.chomp.to_i

if escolha == 1
    if a > c && a > b
        puts"o numero #{a} é o maior"
    elsif c >a && c > b 
        puts"o numero #{c} é o maior"
    elsif b > a && b > c 
        puts"o numero #{b} é o maior"
    end
end 

if escolha == 2
    if a < c && a < b
        puts"o numero #{a} é o menor"
    elsif c < a && c < b 
        puts"o numero #{c} é o menor"
     elsif b < a && b < c 
        puts"o numero #{b} é o menor"
     end
end

if escolha == 3 
        produto = a + b + c 
        puts" O produto é #{produto}"
end
    
if escolha == 4
        media = a + b + c / 3
        puts" a media é #{media}"
end
