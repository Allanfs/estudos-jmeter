Estudo de Teste de Performance com JMeter
===


Informações Importantes
===

- Para testes de performance em **aplicações WEB**: utilizar _HTTP COOKIE MANAGER_ para manter o estado de login
- Para testes de performance em **API**: obter o token (através de _POST PROCESSOR > JSON EXTRACTOR_) de autenticação e utiliza-lo entre diferentes requisições
- Na hora de executar os testes, desabilite o listener _relatório de execução de teste_ e em vez dele utilize _aggregate report_.
- É possível definir variaveis previamente para ser usado nos testes (_Config Element > User Defined Variables_)
