

## Controlled

# Nada mais é do que a gente manter em tempo real o estado a informação que o usuário
# insere em nossa aplicação dentro do estado dentro de uma variável no nosso componente.

# Toda vez que o usuário digita uma informação dentro do input, eu atualizo a informação no estado contendo esse novo valor para que eu possa ter o valor atualizado digitado no input.

# Controlled é manter em tempo real a informação do usuário guardada no estado da nossa aplicação.



# const [ task, setTask ] = useState("");

# <TaskInjput
#   id="task"
#   placeholder="Dê um nome para o seu projeto."
#   onChange={(e) => setTask(e.target.value)}
#   value={task} refletir o valor armazenado no estado ( exemplo quando eu reseto o valor para #   '' após o envio do form)
# />


# Toda vez que rola uma atualização de ESTADO o React faz uma nova renderização, recalcula todo conteúdo do nosso componente.

## Uncontrolled

# A gente busca a informação do valor do input somente quando a gente precisar dela.
# A gente não salva a informação igual no Controlled quando o usuário digita a cada vez no input a informação.


## Casos de Uso do Formulários Controlled 

# Formulários simples com interface simples que contém poucos campos, Form de Login ou Cadastro.

## Casos de uso do Formulários Uncontrolled

# Aplicações que tem muitos formulários, onde você tem infinitos forms pois se armazenar as informações em um estado, toda vez que o estado sofrer alteração nosso componente vai recalcular / fazer uma nova renderização com valor atualizado, se tiver muitos forms isso se torna lento e não performático.




