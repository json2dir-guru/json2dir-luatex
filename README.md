# json2dir-luatex

json2dir in LuaTeX: `json2dir.tex` (run by `luatex --ini --safer`, JSON parsed in `\directlua`) validates the document and writes a shell script; the `json2dir` launcher runs it.

    JSON2DIR_LUATEX=/path/to/luatex ./json2dir < tree.json
