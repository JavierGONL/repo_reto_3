#Reto_3


#### 1.  Plantear el algoritmo para obtener los números primos hasta N, usando pseudocódigo y diagramas de flujo.

- Pseudo Codigo:

------------

 		[VARIABLES]
 	N=Numero entero a saber si es primo o no
 	D=0 <--- Divisores encontrados
 	2 <  C  < N/2 <---- Numeros q dividiran N
 	Mientras  C <= N y D <= 2 Hacer N/C
  	Si N/C == 0 entonces 
    	D=D+1 
	si D == 3 entonces
  	  "No es primo "
	sino 
	  "Es primo "

- Diagrama (solucion muy poco pro)

------------


[![](https://mermaid.ink/img/pako:eNpNkEFPwzAMhf-KlROITYMdK4HEVrjRyzhMtBysxlujNXGVpCDU9b_jNR0iJ9vve7H1BlWzJpWpQ8vfdYM-wnteOZD3fIPtkb2JlqHzxnK4heXyCTal6y15hgI-E7mZ5ttyD4_QmhARNEGCgpRBujU0eBGK1Xo2bSdTPgQCbb6MMMVqDzU7qFEjJGjeJGKL6esRZimf_OeHu8ke2FM4v5RQMFBI917Pm8n7f-BrCTvzBwqnFko2WTRashguvkrFhixVKpNSoz9VqnKjcNhH3v24WmXR97RQfacxUm7w6NFehx26D2ZpD9gG6UmbyP4tZT1FPv4Cv3t47w?type=png)](https://mermaid.live/edit#pako:eNpNkEFPwzAMhf-KlROITYMdK4HEVrjRyzhMtBysxlujNXGVpCDU9b_jNR0iJ9vve7H1BlWzJpWpQ8vfdYM-wnteOZD3fIPtkb2JlqHzxnK4heXyCTal6y15hgI-E7mZ5ttyD4_QmhARNEGCgpRBujU0eBGK1Xo2bSdTPgQCbb6MMMVqDzU7qFEjJGjeJGKL6esRZimf_OeHu8ke2FM4v5RQMFBI917Pm8n7f-BrCTvzBwqnFko2WTRashguvkrFhixVKpNSoz9VqnKjcNhH3v24WmXR97RQfacxUm7w6NFehx26D2ZpD9gG6UmbyP4tZT1FPv4Cv3t47w)


#### 2.Revise el procedimiento matemático para hallar raíces cuadradas (son divisiones y restas), plantee el algoritmo en pseudocódigo y en diagrama de flujo.

- Pseudo Codigo

 			[variables]
		X = numero a calcular raiz cuadrada exacta
  		Y= sqrt X redondeado al entero mas cercano
  		entonces sqrt X y el valor entra en Y Lo redondea
   		Si Y* Y = x
  		"es un numero entero"
   		sino 
		"no es un numero entero" 

------------

- Diagrama

[![](https://mermaid.ink/img/pako:eNptkUFOwzAQRa_y5RWg9gKRikQb2MEGFi1NF4M9pRGJXWwHEpoegFtwNk7CuK2glfDCsq3_5v_xbJR2hlWmlpV71yvyEQ95YSHr6oytdjZ68vBUag7glnSkcI7h8LK3Tc3egXAi--gxnr-RL-mp4pBhig4zLPYlxztwOsLd_-zBICEjhFcJM4Vn46xhMgSqRB8TWFOAZq_JOvSYzA_ig80k2SDfcCV0aKpIxsGwFOPkJbtE6hD4t_g2YXs432WUZo8D9biezy5mo3ZxLIK4nwr7myTD9-cX2oUaKOmyptLI_24SWKi44poLlcnRkH8pVGG3oqMmuvvOapVF3_BANWtDkfOSnj3VKltSFeR1TfbRub87mzI6f7sf4G6O2x_p55nx?type=png)](https://mermaid.live/edit#pako:eNptkUFOwzAQRa_y5RWg9gKRikQb2MEGFi1NF4M9pRGJXWwHEpoegFtwNk7CuK2glfDCsq3_5v_xbJR2hlWmlpV71yvyEQ95YSHr6oytdjZ68vBUag7glnSkcI7h8LK3Tc3egXAi--gxnr-RL-mp4pBhig4zLPYlxztwOsLd_-zBICEjhFcJM4Vn46xhMgSqRB8TWFOAZq_JOvSYzA_ig80k2SDfcCV0aKpIxsGwFOPkJbtE6hD4t_g2YXs432WUZo8D9biezy5mo3ZxLIK4nwr7myTD9-cX2oUaKOmyptLI_24SWKi44poLlcnRkH8pVGG3oqMmuvvOapVF3_BANWtDkfOSnj3VKltSFeR1TfbRub87mzI6f7sf4G6O2x_p55nx)




- codigo python del diagrama

------------


			#variables
	N=int(input("ingrese un numero:"))
	Y= round(sqrt(N))
	 	#solucion
	if Y**2 == N:
		print("es una raiz exacta")
	else:
		print("no es una raiz exacta")

