{
	// Основные настройки редактора
	"window.openFilesInNewWindow": "default",
	"editor.tabSize": 4,
	"editor.folding": true,
	"editor.insertSpaces": true,
	"editor.smoothScrolling": true,
	"editor.minimap.enabled": false,
	"editor.detectIndentation": true,
	"editor.suggestSelection": "first",
	"editor.multiCursorModifier": "ctrlCmd",
	"workbench.tree.indent": 14,
	"workbench.tree.expandMode": "doubleClick",
	"workbench.tree.renderIndentGuides": "none",
	// "workbench.tree.stickyScrollMaxItemCount": 15,

	// Настройки переноса слов
	"editor.wordWrap": "bounded",
	"editor.wrappingIndent": "same",
	"editor.wordWrapColumn": 200,

	// Прокрутка за пределы последней строки
	"editor.scrollBeyondLastLine": true,

	// Связанные редактирования тегов
	"editor.linkedEditing": true,

	// Автоматическое закрытие тегов
	"html.autoClosingTags": true,
	"javascript.autoClosingTags": true,
	"typescript.autoClosingTags": true,

	// Отображение символов
	"editor.renderControlCharacters": false,

	// Подсветка неоднозначных символов
	"editor.unicodeHighlight.ambiguousCharacters": false,

	// Быстрые подсказки
	"html.completion.attributeDefaultValue": "singlequotes",

	// Внешний вид
	"editor.bracketPairColorization.enabled": false,
	"editor.glyphMargin": true,
	"editor.scrollbar.horizontal": "hidden",
	"editor.scrollbar.vertical": "hidden",
	"workbench.productIconTheme": "fluent-icons",
	"window.density.editorTabHeight": "compact",
	"editor.accessibilitySupport": "off",
	"symbols.hidesExplorerArrows": false,
	"workbench.iconTheme": "catppuccin-macchiato",
	"workbench.layoutControl.enabled": false,
	"workbench.editor.editorActionsLocation": "hidden",
	"workbench.editor.empty.hint": "hidden",

	// Настройки курсора
	"editor.cursorBlinking": "expand",
	"editor.cursorStyle": "line",
	"editor.cursorSmoothCaretAnimation": "on",
	"editor.renderLineHighlight": "none",

	// Настройки шрифта
	"editor.fontSize": 15,

	"editor.lineHeight": 1.8,

	"editor.fontWeight": "normal",
	"editor.formatOnType": true,

	"editor.fontLigatures": true,
	"editor.fontFamily": "JetBrains Mono, Fira Code, sans-serif",
	"editor.inlayHints.fontFamily": "PragmataPro",
	"chat.editor.fontFamily": "PragmataPro",
	"editor.codeLensFontFamily": "PragmataPro",
	"debug.console.fontFamily": "PragmataPro",

	// Кастомизация подсветки синтаксиса
	"editor.tokenColorCustomizations": {
		"textMateRules": [
			{
				"scope": [
					"comment",
					"entity.name.type.class",
					"keyword",
					"constant",
					"storage.modifier",
					"storage.type.class.js"
				],
				"settings": {
					"fontStyle": "italic"
				}
			},
			{
				"scope": [
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

	// Настройки терминала
	"terminal.integrated.fontFamily": "JetBrains Mono",
	"terminal.integrated.fontSize": 13,
	"terminal.integrated.tabs.enabled": false,
	"terminal.integrated.cursorStyle": "line",

	// Настройки обозревателя
	"explorer.confirmDelete": false,
	"explorer.confirmDragAndDrop": false,
	"explorer.compactFolders": false,
	"workbench.editor.tabSizing": "fit",
	"workbench.startupEditor": "newUntitledFile",

	// Настройки отладки
	"debug.toolBarLocation": "hidden",
	"debug.focusWindowOnBreak": false,
	"debug.showInlineBreakpointCandidates": false,
	"debug.showBreakpointsInOverviewRuler": false,

	// Настройки Emmet
	"emmet.includeLanguages": {
		"blade": "html",
		"javascript": "javascriptreact"
	},
	"emmet.triggerExpansionOnTab": true,

	// Настройки форматирования
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
	"prettier.arrowParens": "avoid",
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"editor.inlineSuggest.enabled": true,

	// Настройки для Laravel
	"[blade]": {
		"editor.defaultFormatter": "onecentlin.laravel-blade"
	},

	// Настройки для Breadcrumbs
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

	// Настройки для JS и TS
	"javascript.updateImportsOnFileMove.enabled": "always",
	"typescript.updateImportsOnFileMove.enabled": "always",
	"typescript.preferences.quoteStyle": "single",
	"javascript.preferences.quoteStyle": "single",
	"javascript.format.semicolons": "remove",
	"typescript.format.semicolons": "remove",
	"js/ts.implicitProjectConfig.experimentalDecorators": true,

	// Настройки проверки орфографии
	"cSpell.language": "en,ru",
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

	// Разрешенные символы для Unicode Highlight
	"editor.unicodeHighlight.allowedCharacters": {
		"а": true,
		"с": true,
		"Т": true,
		"б": true,
		"е": true,
		" ": true
	},
	"editor.hideCursorInOverviewRuler": true,
	"git.enableSmartCommit": true,

	// Исключаемые файлы
	"files.exclude": {
		"**/.expo": true,
		"**/.expo-shared": true,
		"**/.idea": true,
		"**/.nuxt": true
	},

	// Прочие настройки
	"files.defaultLanguage": "plaintext",
	"diffEditor.ignoreTrimWhitespace": false,
	"security.workspace.trust.untrustedFiles": "open",
	"vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
	"window.confirmBeforeClose": "keyboardOnly",
	"git.openRepositoryInParentFolders": "never",
	"editor.gotoLocation.multipleDefinitions": "goto",
	"editor.stickyScroll.scrollWithEditor": false,
	"workbench.tree.enableStickyScroll": false,
	"editor.stickyScroll.enabled": false,
	"redhat.telemetry.enabled": false,
	"github.copilot.editor.enableAutoCompletions": true,
	"window.commandCenter": false,
	"workbench.editor.customLabels.patterns": {
		"**/app/**/[[]*[]]/[[]*[]]/page.tsx": "${dirname(2)}/${dirname(1)}/${dirname}/page.tsx",
		"**/app/**/[[]*[]]/page.tsx": "${dirname(1)}/${dirname}/page.tsx",
		"**/app/**/page.tsx": "${dirname}/page.tsx",
		"**/app/**/[[]*[]]/[[]*[]]/layout.tsx": "${dirname(2)}/${dirname(1)}/${dirname}/layout.tsx",
		"**/app/**/[[]*[]]/layout.tsx": "${dirname(1)}/${dirname}/layout.tsx",
		"**/app/**/layout.tsx": "${dirname}/layout.tsx"
	},
	"cSpell.userWords": [
		"clsx",
		"recaptcha",
		"sitekey",
		"testid",
		"экспереминтерировать"
	],
	"markdown.updateLinksOnFileMove.enabled": "always",
	"javascript.experimental.updateImportsOnPaste": true,
	"typescript.experimental.updateImportsOnPaste": true,
	"markdown.experimental.updateLinksOnPaste": true,
	"cSpell.autoFormatConfigFile": true,
	"workbench.statusBar.visible": true,
	"files.autoSave": "afterDelay",

	// Live SCSS Compiler
	"liveSassCompile.settings.formats": [
		{
			"format": "expanded",
			"extensionName": ".css",
			"savePath": "src/styles/css/"
		}
	],
	"liveSassCompile.settings.showOutputWindowOn": "None",
	"workbench.colorTheme": "One Dark",
	"liveServer.settings.donotShowInfoMsg": true,
	"editor.mouseWheelZoom": true
}
