# Summary

* [はじめに](README.md)
   * [用語についての注記](terminology-notes.md)
   * [ガイドについての注記](guide-notes.md)
* [ソースファイルの基本事項](source-file-basics.md)
   * [特殊文字](special-characters.md)
       * [空白](whitespace-characters.md)
       * [特別なエスケープシーケンス](special-escape-sequences.md)
       * [非ASCII文字](non-ascii-characters.md)
* [ソースファイルの構造](source-file-structure.md)
   * [ライセンスあるいはコピーライトの情報（もしあるならば）](license_or_copyright_information_if_present.md)
   * [パッケージ文](package_statement.md)
   * [インポート文](import_statements.md)
       * [ワイルドカードインポートは禁止](no_wildcard_imports.md)
       * [改行禁止](no_line-wrapping.md)
       * [順序と空白](ordering_and_spacing.md)
   * [クラス宣言](class_declaration.md)
       * [1つだけのトップレベルクラスの宣言](exactly_one_top-level_class_declaration.md)
       * [クラスメンバーの順序](class_member_ordering.md)
           * [オーバーロードしているメソッド群を分離してはいけません](overloads_never_split.md)
* [フォーマット](formatting.md)
   * Braces
       * [Braces are used where optional](braces_are_used_where_optional.md)
       * [Nonempty blocks: K & R style](nonempty_blocks_k_&_r_style.md)
       * [Empty blocks: may be concise](empty_blocks_may_be_concise.md)
   * [Block indentation: +2 spaces](block_indentation_+2_spaces.md)
   * [One statement per line](one_statement_per_line.md)
   * [Column limit: 80 or 100](column_limit_80_or_100.md)
   * [Line-wrapping](line-wrapping.md)
       * [Where to break](where_to_break.md)
       * [Indent continuation lines at least +4 spaces](indent_continuation_lines_at_least_+4_spaces.md)
   * [Whitespace](whitespace.md)
       * [Vertical Whitespace](vertical_whitespace.md)
       * [Horizontal whitespace](horizontal_whitespace.md)
       * [Horizontal alignment: never required](horizontal_alignment_never_required.md)
   * [Grouping parentheses: recommended](grouping_parentheses_recommended.md)
   * [Specific constructs](specific_constructs.md)
       * [Enum classes](enum_classes.md)
       * [Variable declarations](variable_declarations.md)
           * [One variable per declaration](one_variable_per_declaration.md)
           * [Declared when needed, initialized as soon as possible](declared_when_needed,_initialized_as_soon_as_possi.md)
       * [Arrays](arrays.md)
           * [Array initializers: can be "block-like"](array_initializers_can_be_block-like.md)
           * No C-style array declarations
       * Switch statements
           * Indentation
           * Fall-through: commented
           * The default case is present
       * Annotations
       * Comments
           * Block comment style
       * Modifiers
       * Numeric Literals
* [命名ルール](naming.md)
* [実践的なプログラミング](programming-practices.md)

