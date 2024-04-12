# Setup de pré-commit 🔄️

<ul>
  <li> Boilerplate para React/TypeScript, construído em cima do Vite ⚡️</li>
  <li> Garante que as regras estão seguindo seguidas.</li>
</ul>


# O que há no padrão 

<ul>
  <li>
    <a href='https://vitejs.dev/' target="_blank">Vite</a>
  </li>
  <li>
    <a href='https://react.dev/' target="_blank">React</a>
  </li>
  <li>
    <a href='https://www.typescriptlang.org/'>Typescript</a>
  </li>
  
  <li>Dev Tools</li>

  <ul>
  <li>
    <a href='https://eslint.org/'>Eslint</a>
  </li>
  <li>
    <a href='https://prettier.io/'>Prettier</a>
  </li>
  <li>
    <a href='https://commitlint.js.org/#/'>CommitLint</a>
  </li>
  <li>
    <a href='https://typicode.github.io/husky/#/'>Husky</a>
  </li>
  <li>
    <a href='https://github.com/lint-staged/lint-staged'>Lint-Staged</a>
  </li>
    
  </ul>

</ul>

# Install


Instalando via comando CLI .

Você pode clonar o projeto usando o terminal em sua máquina usando o seguinte comando:

  ```
   git clone: https://github.com/RodrigoHenrique07/Setup-Pre-Commit-Husky.git
  
  ```

então, para iniciar o projeto:

  ``` 
    npm install
    npm run dev

  ```

Observe se o arquivo pre-commit na raiz da pasta husky está com a configuração abaixo ou se esta com 'npm test'. Caso esteja com a segunda opção copie e cole essa configuração:


```
  echo 'Check for linting errors...'
   npx lint-staged || 
  (echo 'Linting errors or tests failed. Please fix them before commiting.' && exit 1)
  
  echo 'Done'
```

#Commitando

A mensagem de commit segue o padrão convencional do commitLint que deve seguir:

``` 
git commit -m 'chore: setup de pre-commit utilizando husky'
```

``` 
git commit -m 'fix: corrigindo bug'
```

``` 
build
chore
ci
docs
feat
fix
perf
refactor
revert
style
test
```




