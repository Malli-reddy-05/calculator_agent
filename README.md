def rule_based_agent(temperature):
if temperature >100:
return "cool"
else:
return "idle"
temperature[80,100,101,120]
for temp in temperatures:
action=rule_based_agent(temp)
print(f"Temperature:{temp}")
print(f"agent action:{action}")
print("-"*30)