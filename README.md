## Verificar versão

- ng version

<br>

## Criar projeto

- ng new projeto-angular

<br>

## Rodar projeto

- ng serve

<br>

## Criar componente

- ng generate component 'nome'

<br>

## Importação manual do componente:

- app.component.ts:

```
import { Componente1Component } from './componente1/componente1.component'
import { Componente2Component } from './componente2/componente2.component'

@Component({
  selector: 'app-root',
  standalone: true,
  imports: [CommonModule, RouterOutlet, Componente1Component, Componente2Component],
...
```

<br>

- app.component.html:

```
<app-componente1></app-componente1>

<app-componente2></app-componente2>
```

<br>

## Importando Bootstrap

- index.html:

```
<head>
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
</head>

<body>
	<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
</body>
```

<br>

app.component.html:

```
<button type="button" class="btn btn-primary">Primary</button>
```

<br>

## Instalando Angular Material no projeto

- ng add @angular/material 
- (y)
- (n)

<br>

## Utilizando Angular Material [Site](https://material.angular.io/)

- app.components.ts:

```
import {MatButtonModule} from '@angular/material/button';

@Component({
  selector: 'app-root',
  standalone: true,
  imports: [CommonModule, RouterOutlet, Componente1Component, Componente2Component, MatButtonModule],
...
```

<br>

- app.component.html:
```
<section>
    <div class="example-label">Raised</div>
    <div class="example-button-row">
      <button mat-raised-button color="primary">Primary</button>
    </div>
  </section>
```

<br>
















<br>

## Aluno

### Lucas Araujo

<a href="https://www.linkedin.com/in/lucarauj"><img alt="lucarauj | LinkdeIN" width="40px" src="https://user-images.githubusercontent.com/43545812/144035037-0f415fc7-9f96-4517-a370-ccc6e78a714b.png" /></a>