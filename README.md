

``` zig
const std = @import("std");

pub fn main() !void {
	const stdout = std.io.getStdOut().writer();
	try stdout.print("👋 Hello Stalkers....")
}
```





