luaconsole_files = files(
	'LegacyLuaAPI.cpp',
	'LuaBit.cpp',
	'LuaButton.cpp',
	'LuaCheckbox.cpp',
	'LuaCompat.c',
	'LuaComponent.cpp',
	'LuaLabel.cpp',
	'LuaProgressBar.cpp',
	'LuaScriptInterface.cpp',
	'LuaSlider.cpp',
	'LuaSmartRef.cpp',
	'LuaTextbox.cpp',
	'LuaWindow.cpp',
)
if uopt_http
	luaconsole_files += files(
		'LuaTCPSocket.cpp',
	)
endif

subdir('luascripts')

powder_files += luaconsole_files
