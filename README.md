Scripts Disponíveis
No diretório do projeto, posso rodar os seguintes comandos:

npm start
Esse comando executa o aplicativo no modo de desenvolvimento. Para visualizar no navegador, basta abrir http://localhost:3000. A página será recarregada automaticamente sempre que eu fizer alterações. Além disso, erros de lint (caso ocorram) serão exibidos no console.

npm test
Esse comando inicia o runner de testes em modo interativo, observando qualquer alteração no código. Se eu precisar de mais informações sobre como executar os testes, posso consultar a seção sobre execução de testes na documentação.

npm run build
Esse comando cria a versão otimizada do meu aplicativo para produção na pasta build. O React será empacotado corretamente em modo de produção e a construção será otimizada para garantir o melhor desempenho. Os arquivos serão minificados, e seus nomes incluirão hashes para controle de cache. Agora, meu aplicativo estará pronto para ser publicado!

Se precisar de mais detalhes sobre como realizar a implantação, posso consultar a documentação específica.

npm run eject
Atenção: Essa é uma operação irreversível. Depois de usar o eject, não tem como voltar atrás!

Se eu não estiver satisfeito com as opções de configuração ou ferramentas de construção, posso usar o comando eject a qualquer momento. Esse comando remove a dependência única de construção do meu projeto e copia todas as configurações e dependências (como webpack, Babel, ESLint, etc.) diretamente para o meu projeto. Com isso, terei controle total sobre elas.

Todos os outros comandos continuarão funcionando normalmente, mas agora apontando para os scripts copiados, que poderei ajustar conforme necessário. A partir desse momento, o gerenciamento do projeto estará completamente sob minha responsabilidade.

Não preciso usar o eject. As configurações padrão atendem bem a projetos pequenos e médios, então não há obrigatoriedade de usá-lo. No entanto, entendo que, quando estiver pronto para personalizar as configurações do projeto, o eject pode ser útil.
