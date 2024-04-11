# -trasa-o-de-euros-para-dollars
passagem de euros para dollars

def converter_para_dolares(euros, taxa_cambio):
    """ Converte um valor em euros para dólares usando a taxa de câmbio fornecida """
    dolares = euros * taxa_cambio
    return dolares



taxa_cambio = 1.08


euros = float(input("Digite o valor em Euros: "))


dolares = converter_para_dolares(euros, taxa_cambio)


print(f"{euros} Euros é igual a {dolares:.2f} Dólares.")


