# Payback

payback.md


# My Awesome Type
This is the documentation for this spectacular type.
### gitbook serve | sir -p 4000 -l
#### This is my awesome 
Here goes some other description of what it is and what is does

fn sum2(n1: i32, n2: i32) -> i32 {
  n1 + n2
}

Here's our logo (hover to see the title text):

Inline-style:
![alt text](image.jpg)


Reference-style:
![alt text1][logo]

[logo]: i-love-markdown.png


# Mermaid mit Hads

	# Hads
##-> Hads is a fast Node.js based web server allowing to browse, search and edit documentation written in Markdown.
	# mermaid
##-> Generation of diagrams and flowcharts from text in a similar manner as markdown.

{% plantuml %}
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
``` 
{% endplantuml %}

```puml
```mermaid
graph LR
A(Weihnachtswünsche: für unsere  AEC-Mitglieder)
B(Wir wünschen Euch zur Weihnachtszeit ein Päckchen voll Gelassenheit,) 
C(die Euch die Weihnachtstage retten,) 
D(die Wogen voller Hektik glätten.)
E(Wir wünschen Euch zur Weihnachtszeit)
F(ein Päckchen voll Besinnlichkeit,) 
G(die Euch die Werte) 
H(lassen erkennen, um sie) 
I(beim wahren Wert zu nennen.)
J(Wir wünschen Euch zur Weihnachtszeit) 
K(ein Päckchen voller Herzlichkeit,) 
L(die Euch Euer Leben) 
M(heller macht,)
N(wenn auch die Sonne mal nicht lacht.)
O(Was jetzt zu wünschen übrig bliebe?) 
P(Ein Päckchen voller Menschenliebe! Nicht nur zur) 
Q(Weihnachtszeit! Wir wünschen es Euch für die ganze Zeit!)
R(In diesem Sinne wünscht der Vorstand)
S(vom AEC RV - Hagen  Euch, Eurer Familie, Euren Freunden)
T(und Bekannten ein besinnliches  Weihnachtsfest und ein gesundes Jahr 2019) 
U(Vorstand)
V(Wolfgang Hengsbach) 
W(Jürgen Heidergott)
X(Hans-Joachim Schober)
Y(Marianne Heidergott)
Z(Rainer Pietron)
...mermaid
```

Documentation:
c:\proggis\xampp\htdocs\rust\libs\java -jar plantuml.jar
```uml
@startuml

    Class Stage
    Class Timeout {
        +constructor:function(cfg)
        +timeout:function(ctx)
        +overdue:function(ctx)
        +stage: Stage
    }
     Stage <|-- Timeout

@enduml
```

# Sequence Diagram
%% Sequence diagram code
sequenceDiagram
    Alice ->> Bob: Hello Bob, how are you?
    Bob-->>John: How about you John?
    Bob--x Alice: I am good thanks!
    Bob-x John: I am good thanks!
    Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

    Bob-->Alice: Checking with John...
    Alice->John: Yes... John, how are you?

mermaid("
graph LR
A(Rounded)-->B[Rectangular]
B-->C{A Rhombus}
C-->D[Rectangle One]
C-->E[Rectangle Two]
")

___

var s = "JavaScript syntax highlighting";
alert(s);
___


# Rust's package manager

USAGE:
    cargo.exe [OPTIONS] [SUBCOMMAND]

OPTIONS:
    -V, --version           Print version info and exit
        --list              List installed commands
        --explain <CODE>    Run `rustc --explain CODE`
    -v, --verbose           Use verbose output (-vv very verbose/build.rs output)
    -q, --quiet             No output printed to stdout
        --color <WHEN>      Coloring: auto, always, never
        --frozen            Require Cargo.lock and cache are up to date
        --locked            Require Cargo.lock is up to date
    -Z <FLAG>...            Unstable (nightly-only) flags to Cargo, see 'cargo -Z help' for details
    -h, --help              Prints help information

Some common cargo commands are (see all commands with --list):
    build       Compile the current package
    check       Analyze the current package and report errors, but don't build object files
    clean       Remove the target directory
    doc         Build this package's and its dependencies' documentation
    new         Create a new cargo package
    init        Create a new cargo package in an existing directory
    run         Build and execute src/main.rs
    test        Run the tests
    bench       Run the benchmarks
    update      Update dependencies listed in Cargo.lock
    search      Search registry for crates
    publish     Package and upload this package to the registry
    install     Install a Rust binary. Default location is $HOME/.cargo/bin
    uninstall   Uninstall a Rust binary

See 'cargo help <command>' for more information on a specific command.


# hads 1.7.1
Usage: C:\node\node.exe C:\Users\Juergen\AppData\Roaming\npm\node_modules\hads\bin\hads [root dir] [options]

Options:
  -p, --port        Port number to listen on                 [default: 4040]
  -h, --host        Host address to bind to                  [default: "localhost"]
  -i, --images-dir  Directory to store images                [default: "images"]
  -o, --open        Open default browser on start          
  -r, --readonly    Read-only mode (no add or edit feature)
  --help            Show this help                         


# kokoi
USAGE

    kokoi [options] [files or dirs]

  Examples:
    kokoi -c "redcarpet --smarty" -s "My Notes" Dir2 test/Foo.md
    kokoi -e rst -c "pandoc -f rst -t html5" foo.rst

  If no file or directory is specified, the current directory (.)
  is assumed. Directories are scanned recursively.
  Subdirectories whose name is "node_modules" or "AppData" or starts
  with a dot (.git, .hg...) are ignored.

OPTIONS

  -p, --port
      TCP port at which the HTML files will be served.
      Default is 8333.

  -c, --command
      Command to convert markup files to HTML.
      Default is "pandoc -f markdown -t -html5".

  -s, --save
      Save the rendered HTML. The output directory for each HTML
      file is the same of the corresponding markup file.

  -m, --mathjax
      Insert a link to the MathJax CDN to render math formulas.
      If the processing engine does not support math formulas
      do not use this option.

  -e, --extensions
      Comma-delimited list of extensions of the files to watch
      for changes, excluding the dots and without spaces.
      Default is "md,markdown".

  -t, --template
      Path to your custom HTML template file. See README.md for
      more information.

  -v, --version
      Show version.

  -h, --help
      Show this help message.

# Hexo
Usage: hexo <command>

Commands:
  help     Get help on a command.
  init     Create a new Hexo folder.
  version  Display version information.

Global Options:
  --config  Specify config file instead of using _config.yml
  --cwd     Specify the CWD
  --debug   Display all verbose messages in the terminal
  --draft   Display draft posts
  --safe    Disable all plugins and scripts
  --silent  Hide output on console

For more help, you can use 'hexo help [command]' for the detailed information
or you can check the docs: http://hexo.io/docs/

# Docsify
Usage: docsify <init|serve> <path>

Commands:
  init <path>   Creates new docs
  serve [path]  Run local server to preview site.
  start <path>  Server for SSR

Global Options
  --help, -h     Show help                                             [boolean]
  --version, -v  Show version number                                   [boolean]

Documentation:
  https://QingWei-Li.github.io/docsify
  https://QingWei-Li.github.io/docsify-cli

Development:
  https://github.com/QingWei-Li/docsify-cli/blob/master/CONTRIBUTING.md

# sir

  Usage: sir [options] <dir>

  Options:

    -V, --version                 output the version number
    -p, --port <port>             specify the port [8080] (default: 8080)
    -h, --hidden                  enable hidden file serving
        --backup <backup-folder>  store copy of each served file in `backup` folder
    -l, --livereload              livereload watching served directory (add `lr` to querystring of requested resource to inject client script)
        --no-logs                 disable request logging
    -f, --format <fmt>            specify the log format string (npmjs.com/package/morgan) (default: dev)
        --minify                  minify code before serving
        --compress                gzip or deflate the response
        --exec <cmd>              execute command on each request
        --no-cors                 disable cross origin access serving
    -a, --agent <user-agent>      set user agent ﬅor proxied urls
    -b, --babel                   pass all js through babel to convert to more js :)
    -h, --help                    output usage information
