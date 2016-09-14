# HW-1
beta = float (input ("What is the beta? "))
RF = float (input("What is the risk free rate? "))
E_Rm = float (input("What is the expected market return?" ))
E_Rp = beta * (E_Rm - RF) + RF
print ("The expected return on the asset is " + str (E_Rp))
# Sample run
# What is the beta? 1.3

# What is the risk free rate? .02

# What is the expected market return? .05
# The expected return on the asset is 0.05900000000000001
