# Calculations
In the examples so far, conditional statements were used to decide how to set the values of variables. But you can also use conditional statements to perform different
calculations.

In this next example, say you live in a country with only two tax brackets. Everyone earning less than 12,000 pays 25% in taxes, and anyone earning 12,000 or more pays 30%.
The function below calculates how much tax is owed:

def get_taxes(earnings):
    if earnings < 12000:
        tax_owed = .25 * earnings
    else:
        tax_owed = .30 * earnings
    return tax_owed


The next code cell uses the function:

ana_taxes = get_taxes(9000)
bob_taxes = get_taxes(15000)
print(ana_taxes)
print(bob_taxes)

2250.0
4500.0


In each case, we call the get_taxes() function and use the value that is returned to set the value of a variable.
1} For ana_taxes, we calculate taxes owed by a person who earns 9,000. In this case, we call the get_taxes() function with earnings set to 9000. Thus, earnings < 12000
is True, and tax_owed is set to .25 * 9000. Then we return the value of tax_owed.
2} For bob_taxes, we calculate taxes owed by a person who earns 15,000. In this case, we call the get_taxes() function with earnings set to 15000. Thus, earnings < 12000
is False, and tax_owed is set to .30 * 15000. Then we return the value of tax_owed.
