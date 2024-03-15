def calcular_imposto(valor):
    pis = 0.0165
    confins = 0.07
    imposto_pis = valor * pis
    imposto_confins = valor * confins
    return pis, confins, imposto_pis, imposto_confins

valor = float(input("Digite o valor para calcular os impostos: "))

pis, confins, imposto_pis, imposto_confins = calcular_imposto(valor)
print(f"Valor do imposto PIS: {imposto_pis}")
print(f"Valor do imposto COFINS: {imposto_confins}")
