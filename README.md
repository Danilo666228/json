{
	"files.autoSave": "afterDelay",

	//Main editor settings
	"window.openFilesInNewWindow": "off",
	"editor.tabSize": 4,
	"editor.folding": false,
	"editor.insertSpaces": false,
	"editor.smoothScrolling": true,
	"editor.minimap.enabled": false,
	"editor.detectIndentation": true,
	"editor.suggestSelection": "first",
	"editor.multiCursorModifier": "ctrlCmd",
	"window.zoomLevel": 0.5,

	"workbench.tree.renderIndentGuides": "none",
	// Wrapping
	"editor.wordWrap": "bounded",
	"editor.wrappingIndent": "same",
	"editor.wordWrapColumn": 80,

	//Определяет, будет ли редактор прокручиваться за пределы последней строки.
	"editor.scrollBeyondLastLine": true,
	// Rename tags
	"editor.linkedEditing": true,

	// Auto closing tags
	"html.autoClosingTags": true,
	"javascript.autoClosingTags": true,
	"typescript.autoClosingTags": true,

	//Определяет, должен ли редактор отображать управляющие символы.
	"editor.renderControlCharacters": false,

	//Управляет выделением символов, которые можно спутать с основными символами ASCII, кроме тех, которые являются общими для текущего пользовательского языкового стандарта.
	"editor.unicodeHighlight.ambiguousCharacters": false,

	"editor.quickSuggestionsDelay": 0,
	"html.completion.attributeDefaultValue": "singlequotes",

	//Appearance
	"editor.bracketPairColorization.enabled": false,
	"editor.glyphMargin": false,
	"editor.scrollbar.horizontal": "hidden",
	"editor.scrollbar.vertical": "hidden",
	"workbench.productIconTheme": "fluent-icons",
	"window.density.editorTabHeight": "compact",
	"workbench.colorTheme": "Atom Material Theme",
	"editor.accessibilitySupport": "off",
	"window.commandCenter": false,
	"workbench.layoutControl.enabled": false,
	"symbols.hidesExplorerArrows": false,
	"workbench.iconTheme": "moxer-icons",

	// Cursor
	"editor.cursorBlinking": "expand",
	"editor.cursorStyle": "line",
	"editor.cursorSmoothCaretAnimation": "on",

	// Font
	"editor.fontWeight": "normal",
	"editor.fontSize": 13,
	"editor.fontVariations": true,
	"editor.lineHeight": 25,
	"editor.fontLigatures": false,
	"editor.renderLineHighlight": "none",
	"editor.fontFamily": "JetBrains Mono, Operator mono lig, Iosevka NFM, Monaspace Neon, Maple Mono, MonoLisa, Ubuntu Mono, DejaVu Sans Mono, Fira Code, monoki, Hasklig, PragmataPro, IBM Plex Mono, Victor Mono, Roboto Mono, monospace",
	"editor.inlayHints.fontFamily": "JetBrains Mono",

	"editor.tokenColorCustomizations": {
		"textMateRules": [
			{
				"scope": [
					//following will be in italic
					"comment",
					"entity.name.type.class", //class names
					"keyword", //import, export, return…
					"constant", //String, Number, Boolean…, this, super
					"storage.modifier", //static keyword
					"storage.type.class.js" //class keyword
				],
				"settings": {
					"fontStyle": "italic"
				}
			},
			{
				"scope": [
					//following will be excluded from italics (VSCode has some defaults for italics)
					"invalid",
					"keyword.operator",
					"constant.numeric.css",
					"keyword.other.unit.px.css",
					"constant.numeric.decimal.js",
					"constant.numeric.json"
				],
				"settings": {
					"fontStyle": ""
				}
			}
		]
	},

	//Terminal
	"terminal.integrated.fontFamily": "JetBrains Mono",
	"terminal.integrated.fontSize": 13,
	"terminal.integrated.tabs.enabled": false,

	//Explorer
	"explorer.confirmDelete": false,
	"explorer.compactFolders": false,
	"explorer.confirmDragAndDrop": false,
	//Разрешить уменьшение размера вкладок, когда доступного места недостаточно для отображения всех вкладок одновременно.
	"workbench.editor.tabSizing": "fit",
	"workbench.startupEditor": "newUntitledFile",

	//Debug
	"debug.toolBarLocation": "hidden",
	"debug.focusWindowOnBreak": false,
	"debug.showInlineBreakpointCandidates": false,
	"debug.showBreakpointsInOverviewRuler": false,

	// Emmet
	"emmet.includeLanguages": {
		"blade": "html",
		"javascript": "javascriptreact"
	},
	"emmet.triggerExpansionOnTab": true,

	//Format
	"prettier.semi": false,
	"prettier.useTabs": true,
	"editor.formatOnSave": true,
	"prettier.singleQuote": true,
	"prettier.jsxSingleQuote": true,
	"editor.codeActionsOnSave": {
		"source.organizeImports": "explicit"
	},
	"[prisma]": {
		"editor.defaultFormatter": "Prisma.prisma"
	},
	//Включите круглые скобки вокруг единственного параметра функции стрелки
	"prettier.arrowParens": "avoid",
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	// "files.associations": { "*.scss": "postcss", "*.module.scss": "postcss" },
	"editor.inlineSuggest.enabled": true,

	//Laravel
	"[blade]": {
		"editor.defaultFormatter": "onecentlin.laravel-blade"
	},
	"[php]": {
		"editor.defaultFormatter": "DEVSENSE.phptools-vscode"
	},

	//Breadcrumbs
	"breadcrumbs.icons": false,
	"breadcrumbs.showKeys": false,
	"breadcrumbs.showFiles": false,
	"breadcrumbs.symbolPath": "off",
	"breadcrumbs.showArrays": false,
	"breadcrumbs.showEvents": false,
	"breadcrumbs.showFields": false,
	"breadcrumbs.showClasses": false,
	"breadcrumbs.showMethods": false,
	"breadcrumbs.showBooleans": false,
	"breadcrumbs.showFunctions": false,
	"breadcrumbs.showConstants": false,
	"breadcrumbs.showEnumMembers": false,
	"breadcrumbs.showConstructors": false,

	//JS & TS
	"javascript.updateImportsOnFileMove.enabled": "always",
	"typescript.updateImportsOnFileMove.enabled": "always",
	"typescript.preferences.quoteStyle": "single",
	"javascript.preferences.quoteStyle": "single",
	"javascript.format.semicolons": "remove",
	"typescript.format.semicolons": "remove",
	// Использование экспериментальных декораторов в JS/TS
	"js/ts.implicitProjectConfig.experimentalDecorators": true,

	//Spell checker
	"cSpell.language": "en,ru",
	"cSpell.userWords": [],
	"cSpell.enabled": true,
	"cSpell.enableFiletypes": [
		"blade",
		"jsx",
		"tsx",
		"ts",
		"js",
		"scss",
		"sass",
		"vue"
	],

	"editor.unicodeHighlight.allowedCharacters": {
		"а": true,
		"с": true,
		"Т": true,
		"б": true,
		"е": true
	},
	"editor.hideCursorInOverviewRuler": true,
	"git.enableSmartCommit": true,

	"files.exclude": {
		"**/.expo": true,
		"**/.expo-shared": true,
		"**/.idea": true,
		"**/.next": true,
		"**/.nuxt": true,
		"**/dist": true
	},

	// OTHER
	// Язык по умолчанию для новых файлов
	"files.defaultLanguage": "plaintext",
	// Игнорировать пробелы при сравнении в редакторе diff
	"diffEditor.ignoreTrimWhitespace": false,
	// Открытие не доверенных файлов без предупреждения
	"security.workspace.trust.untrustedFiles": "open",
	// Автоматически изменять предложение автозаполнения на основе предыдущего выбора
	"vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
	// Подтверждение перед закрытием окна только при использовании клавиатуры
	"window.confirmBeforeClose": "keyboardOnly",
	// Не открывать репозиторий в родительских папках
	"git.openRepositoryInParentFolders": "never",

	// Поведение при обнаружении нескольких определений
	"editor.gotoLocation.multipleDefinitions": "goto",
	// Скрыть подсказку в пустом редакторе
	"workbench.editor.empty.hint": "hidden",
	"workbench.colorCustomizations": {
		"terminal.background": "#00000000"
	},
	"workbench.settings.applyToAllProfiles": ["workbench.colorCustomizations"],
	"window.titleBarStyle": "custom",
	"vscode_vibrancy.opacity": 0.9,
	"workbench.tree.indent": 15,
	"workbench.tree.expandMode": "doubleClick"
}
