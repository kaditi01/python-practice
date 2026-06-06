#Temperature Converter

def cel_to_fah(c):
    return (c * 9/5) + 32

temp = float(input("Enter temperature in Celsius: "))
result = cel_to_fah(temp)

print("Temperature in Fahrenheit:", result)
