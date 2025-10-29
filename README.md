# 📘 Dicionário SwiftUI — Propriedades mais utilizadas e suas descrições

Um guia prático das propriedades mais usadas no **SwiftUI**, com explicações diretas e exemplos simples.  
Ideal para quem está migrando de UIKit ou quer escrever interfaces mais limpas e previsíveis. 🚀  

---

## 🧱 Estrutura e Layout

| Propriedade | Descrição |
|--------------|------------|
| `body` | Define o conteúdo visual da view (obrigatória). |
| `frame(width:height:alignment:)` | Controla tamanho e alinhamento da view. |
| `padding(_:)` | Adiciona espaçamento interno. |
| `background(_:)` | Define cor ou view de fundo. |
| `cornerRadius(_:)` | Arredonda os cantos. |
| `shadow(radius:)` | Adiciona sombra à view. |
| `overlay(_:)` | Coloca uma view sobre outra. |
| `opacity(_:)` | Controla a transparência (0 a 1). |

---

## 🎨 Estilo e Texto

| Propriedade | Descrição |
|--------------|------------|
| `font(_:)` | Define o tamanho e peso da fonte. |
| `foregroundColor(_:)` | Define a cor do texto ou ícone. |
| `multilineTextAlignment(_:)` | Alinha textos longos. |
| `lineLimit(_:)` | Limita o número de linhas exibidas. |
| `truncationMode(_:)` | Define onde cortar o texto (head, middle, tail). |

---

## 📲 Interações e Eventos

| Propriedade | Descrição |
|--------------|------------|
| `onTapGesture(_:)` | Executa ação ao toque. |
| `onAppear(_:)` | Chamado quando a view aparece. |
| `onDisappear(_:)` | Chamado quando a view sai da tela. |
| `gesture(_:)` | Detecta gestos personalizados (drag, long press, etc). |
| `disabled(_:)` | Desabilita interação do usuário. |
| `buttonStyle(_:)` | Aplica estilo a botões. |

---

## 🧭 Navegação

| Propriedade | Descrição |
|--------------|------------|
| `NavigationStack` | Controla navegação hierárquica (iOS 16+). |
| `NavigationLink` | Cria link entre telas. |
| `navigationTitle(_:)` | Define título da barra de navegação. |
| `navigationBarTitleDisplayMode(_:)` | Controla modo do título (inline, large). |
| `sheet(isPresented:)` | Abre uma tela modal. |
| `fullScreenCover` | Exibe uma tela em modo fullscreen. |

---

## 🧠 Gerenciamento de Estado

| Propriedade | Descrição |
|--------------|------------|
| `@State` | Estado local mutável da view. |
| `@Binding` | Conecta estados entre views (two-way binding). |
| `@ObservedObject` | Observa um objeto externo que conforma `ObservableObject`. |
| `@StateObject` | Cria e mantém um objeto observável. |
| `@EnvironmentObject` | Compartilha estado global. |
| `@Environment` | Acessa propriedades do ambiente (ex: dismiss). |

---

## 📦 Listas e Coleções

| Propriedade | Descrição |
|--------------|------------|
| `List` | Exibe lista rolável de elementos. |
| `ForEach` | Itera sobre uma coleção. |
| `ScrollView` | Permite rolagem vertical ou horizontal. |
| `LazyVStack` / `LazyHStack` | Renderiza sob demanda (melhor performance). |

---

## 🧰 Containers e Estrutura

| Propriedade | Descrição |
|--------------|------------|
| `VStack`, `HStack`, `ZStack` | Organizadores verticais, horizontais e sobrepostos. |
| `Spacer()` | Cria espaço flexível entre views. |
| `Divider()` | Linha separadora visual. |
| `Group` | Agrupa views sem alterar layout. |

---

## ✨ Extras Úteis

| Propriedade | Descrição |
|--------------|------------|
| `clipShape(_:)` | Recorta a view em um formato. |
| `aspectRatio(_:)` | Mantém proporção da view ou imagem. |
| `animation(_:)` | Adiciona animação à mudança de estado. |
| `transition(_:)` | Define como a view entra/sai da tela. |
| `task { }` | Executa código assíncrono quando a view carrega. |

---
