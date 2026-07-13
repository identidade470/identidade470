## About me 👋

```lua

local Human = {}
Human.__index = Human

function Human.new()
  local self = setmetatable({}, Human)

  self.Name = "Gabriel"
  self.UserName = "IDENTIDADE470"

  self.Gender = "Male"
  self.Languages = {
    "English",
    "Brazilian Portuguese"
  }
  self.ProgrammingLanguages = {
    "C++",
    "Lua / Luau",
    "Java"
  }

  return self
end

return Human

```
