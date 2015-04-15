# gtihubtest
This is my first repository on github


lua language

function power(x)
  return function(y) return y ^ x
          end
end

local power2 = power(2)
local power3 = power(3)

print(power2(4))   --the result is 16
print(power3(5))   --the result is 125


--lua 的单行注释
--[[ lua 的多行注释
是这样的]]
