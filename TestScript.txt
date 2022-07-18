r = require("robot");

local moveDistance = io.read();


print("Moving " + moveDistance + " Blocks");

for i = 0, moveDistance, 1 do
    r.moveForward();
end
--