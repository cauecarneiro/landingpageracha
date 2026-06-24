# racha.

Landing page do **racha.**, um app de divisão de despesas em grupo para viagens, repúblicas, rolês e casais.

## Sobre

Página de marketing com foco em conversão para download do app. Design editorial e premium com efeitos de scroll, scrollytelling com celular sticky e animações de reveal.

## Tecnologias

- HTML5 semântico
- CSS3 (animações, grid, flexbox, clamp, sticky)
- JavaScript vanilla (scroll-linked animations, IntersectionObserver, count-up)
- Google Fonts: Bricolage Grotesque, Instrument Serif, Schibsted Grotesk, JetBrains Mono

## Seções

- **Hero** com celular mockup e cards flutuantes com parallax
- **Scrollytelling** com celular sticky que troca de tela conforme o scroll (Home, Adicionar Despesa, Saldos, Pago)
- **Recursos** em bento grid assimétrico
- **Números** com contadores animados (count-up)
- **Depoimento** em estilo pull-quote editorial
- **CTA** com fundo lima e watermark gigante
- **Footer** com colunas de links

## Design Tokens

| Token | Cor |
|---|---|
| Paper (fundo claro) | `#F3F1EA` |
| Ink (texto/fundo escuro) | `#14130E` |
| Lima (acento/CTA) | `#C9F24A` |
| Verde (a receber) | `#1E9E6A` |
| Coral (a pagar) | `#F0533B` |

## Como rodar

```bash
# Servidor local com Python
python3 -m http.server 3000

# Abrir no navegador
open http://localhost:3000
```

## Responsivo

- **Desktop** (>1024px): layout completo com scrollytelling e bento grid
- **Tablet/Mobile** (<1024px): layout empilhado, scrollytelling simplificado

## Acessibilidade

Respeita `prefers-reduced-motion`: desativa parallax, float e count-up, revelando o conteúdo imediatamente.
