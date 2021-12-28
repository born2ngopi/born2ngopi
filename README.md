

``` zig
const print = @import("std").debug.print;

const Myself = struct{
	name: [19:0]u8,
	from: [10:0]u8,
};

pub fn main() !void {

	print("👋 Hello Stalkers....",.{});

	const introduct = Myself{
		.name = "chandra agung rizky".*,
		.from = "yogyakarta".*,
	};

	_ = introduct;
}
```





