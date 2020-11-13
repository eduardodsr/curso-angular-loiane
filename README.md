# Curso Angular - Loiane Training
 
 Curso Angular Gratuito
=======================

[![Open in Visual Studio Codespaces](https://img.shields.io/endpoint?style=social&url=https%3A%2F%2Faka.ms%2Fvso-badge)](https://online.visualstudio.com/environments/new?name=Curso%20Angular&repo=loiane/curso-angular)

Código fonte apresentado no curso de Angular gratuito do blog loiane.com - loiane.training

**Código atualizado para Angular v10**

### Link do curso com certificado:
* [http://loiane.training/curso/angular/](http://loiane.training/curso/angular/)

### Playlist Youtube
* [Clique aqui para assistir a todos os vídeos já publicados](https://www.youtube.com/playlist?list=PLGxZ4Rq3BOBoSRcKWEdQACbUCNWLczg2G)

### Editor e plugins

Particularmente recomendo o uso do Visual Studio Code como editor - que é o mesmo usado nas aulas.

Para pacote de plugins, instale esse pacote de extensões VSCode que contém todos os plugins mostrados durante as aulas do curso: [https://marketplace.visualstudio.com/items?itemName=loiane.angular-extension-pack](https://marketplace.visualstudio.com/items?itemName=loiane.angular-extension-pack).

### Lista das aulas

Aulas publicadas/programadas

#### Introdução
* 01: Introdução + Arquitetura ✔️
* 02: Ambiente de desenvolvimento ✔️
* 03: Primeira app (Hello World) ✔️
* 04: Introdução ao Typescript para Angular ✔️
* 05: Módulos (ngModule) ✔️
* 06: Templates ✔️
* 07: Serviços (Services) e Injeção de dependência (DI) :x:
* 08: Dica de produtividade: code snippets :x:

#### Data binding e eventos
* 09: Property binding + Interpolation :x:
* 10: Class e Style binding :x:
* 11: Event binding :x:
* 12: Two-way data binding :x:
* 13: Input properties :x:
* 14: Output properties :x:
* 15: Ciclo de vida (life-cycle) do Componente :x:
* 16: Acesso à variáveis locais do Template com ViewChild :x:
* Extra: Atualizações do RC 5 e ngModule :x:

#### Angular CLI: Introdução
* 17: Angular CLI: Instalação e criação de projetos: ng new e ng serve :x:
* 18: Angular CLI: Criando components, services: ng generate :x:
* Extra: Angular CLI: atualizando para versão RC5 (webpack) :x:
* 19: Angular CLI: Usando pré-processadores (Sass, Less, Stylus) :x:
* 20: Angular CLI: ng lint, ng test, ng e2e :x:
* 21: Angular CLI: Estrutura do projeto :x:
* 22: Angular CLI: Fazendo build :x:
* 23: Angular CLI: instalando bibliotecas (bootstrap, materialize, lodash, jquery, etc) :x:

#### Diretivas
* 24: Introdução e tipos de diretivas no Angular 2 :x:
* 25: ngIf :x:
* 26: ngSwitch :x:
* 27: ngFor :x:
* 28: sobre o asterisco :x:
* 29: ngClass :x:
* 10: ngStyle :x:
* 31: operador elvis :x:
* 32: ng-content :x:
* 33: Criando uma diretiva de atributo  :x:
* 34: HostListener e HostBinding :x:
* 35: Property Binding de Diretivas :x:
* 36: Criando uma diretiva de estrutura (ngElse)  :x:

## Serviço (Service) e Injeção de Dependência (DI)
* 37: Introdução a Serviços :x:
* 38: Criando um serviço (Service)  :x:
* 39: Injeção de Dependência (DI) + como usar um serviço em um componente  :x:
* 40: Escopo de instâncias de serviços e módulos  :x:
* 41: Injetando um serviço em outro serviço  :x:
* 42: Comunicação entre componentes usando serviços  :x:

## Pipes
* 43: Pipes (usando pipes, parâmetros e pipes aninhados)  :x:
* 44: Criando um Pipe  :x:
* 45: Aplicando Locale (internacionalização) nos Pipes  :x:
* 46: Pipes: Criando um Pipe "Puro  :x:
* 47: Pipes: Criando um Pipe "Impuro"  :x:
* 48: Pipes: Async  :x:

## Rotas
* 49: Rotas: Introdução  :x:
* 50: Rotas: Configurando rotas simples :x:
* 51: Rotas: RouterLink: definindo rotas no template :x:
* 52: Rotas: Aplicando CSS em rotas ativas-k :x:
* 53: Rotas: Definindo e extraindo parâmetros de roteamento :x:
* 54: Rotas: Escutando mudanças nos parâmetros de roteamento :x:
* 55: Rotas Imperativas: Redirecionamento via código :x:
* 56: Rotas: Definindo e extraindo parâmetros de url (query) :x:
* 57: Rotas: Criando um módulo de rotas :x:
* 58: Criando um módulo de funcionalidade :x:
* 59: Rotas: Criando um módulo de rotas de funcionalidade :x:
* 60: Rotas Filhas :x:
* 61: Rotas Filhas: desenvolvendo as telas :x:
* 62: Rotas: Dica de Performance: Carregamento sob demanda (lazy loading) :x:
* 63: Rotas: Tela de Login e como não mostrar o Menu (NavBar) :x:
* 64: Usando Guarda de Rotas: CanActivate :x:
* 65: Usando Guarda de Rotas: CanActivateChild :x:
* 66: Usando Guarda de Rotas: CanDeactivate :x:
* 67: Usando Guarda de Rotas: CanDeactivate com Interface Genérica :x:
* 68: Resolve: carregando dados antes da rota ser ativada :x:
* 69: CanLoad: como não carregar a rota/módulo sem permissão :x:
* 70: Definindo rota padrão e wildcard (rota não encontrada) :x:
* 71: Estilo de url: HTML5 ou usando # :x:

## Formulários (Templates)
* 72: Formulários (template vs data / reativo) Introdução :x:
* 73: Formulários - Criando o projeto inicial com Bootstrap 3 :x:
* 74: Forms (template driven) Controles ngForm, ngSubmit e ngModel :x:
* 75: Forms (template driven) Inicializando valores com ngModel :x:
* 76: Forms (template driven) Módulos e FormsModule :x:
* 77: Forms (template driven) Aplicando validação nos campos :x:
* 78: Forms (template driven) Aplicando CSS na validação dos campos :x:
* 79: Forms (template driven) Mostrando mensagens de erro de validação :x:
* 80: Forms (template driven) Desabilitando o botão de submit para formulário inválido :x:
* 81: Forms (Dica): Verificando dados do Form no template com JSON :x:
* 82: Forms (template driven) Adicionando campos de endereço (form layout Bootstrap 3) :x:
* 83: Forms (template driven) Refatorando (simplificando) CSS e mensagens de erro :x:
* 84: Forms (template driven) Form groups (agrupando dados) :x:
* 85: Forms (template driven) Pesquisando endereço automaticamente com CEP :x:
* 86: Forms (template driven) Populando campos com setValue e patchValue (CEP) :x:
* 87: Forms (template driven) Submetendo valores com HTTP POST :x:

## Formulários (Reativos)
* 88: Formulários reativos (data driven) Introdução :x:
* 89: Formulários reativos: Configuração (Módulo e Componente) :x:
* 90: Formulários reativos: Criando um form com código Angular :x:
* 91: Formulários reativos: Sincronizando HTML com FormGroup :x:
* 92: Formulários reativos: Fazendo submit :x:
* 93: Resetando o form :x:
* 94: Formulários reativos: Aplicando validação nos campos :x:
* 95: Formulários reativos: Acesso ao FormControl no HTML e CSS de validação dos campos :x:
* 96: Formulários reativos: Endereço (migrando de template driven para form reativo) :x:
* 97: Formulários reativos: Form groups (agrupando dados) :x:
* 98: Formulários reativos: Autopopulando endereço com CEP (setValue e patchValue) :x:
* 99: Formulários reativos: Verificar validação dos campos com botão submit :x:
* 100: Formulários: Criando um serviço de Estados Brasileiros :x:
* 101: Formulários: Serviço de consulta CEP + provideIn :x:
* 102: Formulários reativos: Combobox simples (select) :x:
* 103: Formulários reativos: Combobox com Objeto (ngValue e compareWith) :x:
* 104: Formulários reativos: Combobox Múltiplo (Select Multiple) :x:
* 105: Formulários reativos: Radio Button (Botão do tipo Rádio) :x:
* 106: Formulários reativos: Checkbox Toggle :x:
* 107: Formulários reativos: FormArray: Checkboxes Dinâmicos :x:
* 108: Formulários reativos: Validação Customizada (FormArray Checkboxes) :x:
* 109: Formulários reativos: Validação Customizada (CEP) :x:
* 110: Formulários reativos: Validação entre dois campos (confirmar email) :x:
* 111: Formulários reativos: Validação Assíncrona :x:
* 112: Formulários reativos: Serviço de Mensagens de Erros :x:
* 113: Formulários reativos: Reagindo à mudanças reativamente :x:
* 114: Formulários reativos: Campo input customizado (ControlValueAcessor) :x:
* 115: Formulários reativos: Classe base para Forms (herança no Angular) :x:
* 116: Formulários reativos: Combobox aninhado: Estado + Cidade :x:

## Integração com server
* 117: Http / HttpClient: Introdução :x:
* 118: Instalando Bootstrap 4 :x:
* 119: Http: Simulando Servidor REST (json-server) :x:
* 120: Http GET: listar registros :x:
* 121: Http: Dica: Variável de Ambiente :x:
* 122: Http GET + Pipe Async :x:
* 123: Http + RxJS: Unsubscribe Automático :x:

