# CRC_unit_calculation

Introduction: This program was developed as a work in the discipline of Embedded Systems Programming at UFMG - Prof. Ricardo de Oliveira Duarte - Department of Electronic Engineering. The program was developed and tested with Stm32F401RE (Nucleo 64 board).

O intuito desse programa é mostrar de maneira didática como realizar o cálculo do CRC de um conjunto de dados utilizando a unidade de cálculo de CRC disponível nos microcontroladores STM32. O programa foi desenvolvido para a placa Stm32F401RE (Nucleo 64).

Esse exemplo consiste basicamente em definir um vetor de dados, realizar o cálculo do CRC sobre ele e comparar o valor obtido com um resultado conhecido para o conjunto de dados especificado (resultado obtido de  https://crccalc.com/). A indicação se o valor calculado confere com o esperado foi realizada através de um LED (disponível na própia placa). O LED pincando a cada 1 segundo indica que o CRC calculado está correto, de acordo com o especificado. Ja no caso de ele estar piscando a cada 100ms indica que o CRC está diferente do valor esperado. 


Para mais informações entre em contato com os desenvolvedores:

Amanda Alkmim Rezende Teixeira: amandaarteixeira@hotmail.com e Vitor Gabrie Reis Caitite: vitorgabriel1000@hotmail.com.
