---
description: Ceci est une description de la page.
---

# Introduction

## Sous-partie

Texte en **gras** et en _italique_.

Ca serait bien [d'améliorer le chapitre Prévention](broken-reference).

Dans la section épidémiologique, nous aborderons la prévalence du VIH et également le concept d'_incidence_.

> Ceci est une citation.
>
> _Auteur inconnus_

## Seconde sous-partie

### Titre de niveau 2

#### Titre de niveau 3

Il est possible de faire des encadrés (voir ci-dessous).

{% hint style="info" %}
**ATTENTION**

Ceci est une information mise en lumière
{% endhint %}

{% tabs %}
{% tab title="R" %}
```r
mean(1:6)
```
{% endtab %}

{% tab title="Résultat" %}
```
3.5
```
{% endtab %}
{% endtabs %}

Table 1: Titre du tableau (Pandoc caption ne marche pas)

**Titre du tableau juste en gras.**

| xccccc |  xxxxx  |
| ------ | :-----: |
| ccc    |   cccc  |
| ccccc  | aaaaaaa |

![Titre de l'image](.gitbook/assets/image.jpg)

{% content-ref url="broken-reference" %}
[Broken link](broken-reference)
{% endcontent-ref %}

{% tabs %}
{% tab title="First Tab" %}
texte du premier onglet

On peut utiliser une mise en forme avancée.
{% endtab %}

{% tab title="Second Tab" %}

{% endtab %}
{% endtabs %}

## Peut-on faire des notes de bas de page ?

Ceci est un essai (exemple) de note^\[Ceci est le texte de la note] de bas de page. Est-ce possible ? Il semble que les notes de bas de page ne soit pas (encore ?) prise en compte par Gitbook.

## Encadrés

{% hint style="info" %}
**terme :** j'indique ici la définition d'un terme spécifique via un encadré.
{% endhint %}

Il existe différents types d'encadrés.

{% hint style="warning" %}
On peut indiquer un point d'attention.
{% endhint %}

{% hint style="danger" %}
Des mauvaises pratiques. On un risque.
{% endhint %}

{% hint style="success" %}
Ou des bonnes pratiques.
{% endhint %}

## Vidéo

{% embed url="https://youtu.be/W5F6kvCMosc" %}

