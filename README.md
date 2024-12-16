# Introdução
Um ingrediente-chave de sistemas que visam lidar com múltiplas representações de características geográficas é algum método para avaliar a correspondência e similaridade de tais representações. 
Em outras palavras, dados dois objetos de duas fontes de dados diferentes, deve-se ser capaz de dizer se eles modelam o mesmo objeto do mundo real e, neste caso, medir seu grau de similaridade.

Este plugin é uma implementação do Método de Retângulos Equivalentes (ERM) para quantificar a distância média entre representações cartográficas ambíguas e usa o Índice de Similaridade Cartográfica (CSI) 
ou Índice de Similaridade Geográfica (CSI) – um índice baseado em distâncias de área – para avaliar o quanto uma dada representação geométrica se assemelha a outra. No momento, este plugin funciona comparando duas camadas. 
Cada camada deve ter apenas um polígono.

____

A key ingredient of systems aiming to cope with multiple representations of geographic features is some method for assessing the
correspondence and similarity of such representations. In other words, given two objects from two different data sources, 
one must be able to tell whether they model the same real world object and, in this case, measure their degree of similarity. 

This plugin is an implementation of the Equivalents Rectangles Method (ERM) to quantify the average distance between ambiguous cartographic representations and uses the Cartographic Similarity Index (CSI) 
or Geographic Similarity Index (CSI)  – an index based on areal distances – to evaluate how much a given geometric representation resembles another. At the moment this plugin works by comparing two layers. Each layer must have only one polygon.
