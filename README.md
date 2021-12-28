

``` rust
struct Introduct {
    name: String,
    from: String,
    languages: [String; 2],
    languages_technology: [String; 5],
}

impl Introduct {
    fn myself() -> Introduct {
        Introduct{
            name: "Chandra Agung Rizky".to_string(),
            from: "Yogyakarta, Indonesia".to_string(),
            languages: [
                "Indonesia".to_string(),
                "English".to_string(),
            ],
            languages_technology: [
                "Golang".to_string(),
                "Rust".to_string(),
                "Php".to_string(),
                "Javascript".to_string(),
                "Ruby".to_string(),
            ],
        }
    }
}

fn main(){
    println!("👋 Hello Stalkers......");
    
    Introduct::myself();
}

```







