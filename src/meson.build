gala_bin_sources = files(
	'DBus.vala',
	'DBusAccelerator.vala',
	'DockThemeManager.vala',
	'DragDropAction.vala',
	'InternalUtils.vala',
	'KeyboardManager.vala',
	'Main.vala',
	'MediaFeedback.vala',
	'PluginManager.vala',
	'ScreenSaver.vala',
	'ScreenshotManager.vala',
	'Settings.vala',
	'ShadowEffect.vala',
	'TextShadowEffect.vala',
	'WindowListener.vala',
	'WindowManager.vala',
	'WorkspaceManager.vala',
	'Background/Animation.vala',
	'Background/Background.vala',
	'Background/BackgroundCache.vala',
	'Background/BackgroundContainer.vala',
	'Background/BackgroundManager.vala',
	'Background/BackgroundSource.vala',
	'Background/SystemBackground.vala',
	'Widgets/IconGroup.vala',
	'Widgets/IconGroupContainer.vala',
	'Widgets/MonitorClone.vala',
	'Widgets/MultitaskingView.vala',
	'Widgets/SafeWindowClone.vala',
	'Widgets/SelectionArea.vala',
	'Widgets/WindowClone.vala',
	'Widgets/WindowCloneContainer.vala',
	'Widgets/WindowIconActor.vala',
	'Widgets/WindowMenu.vala',
	'Widgets/WindowOverview.vala',
	'Widgets/WindowSwitcher.vala',
	'Widgets/WorkspaceClone.vala',
	'Widgets/WorkspaceInsertThumb.vala',
)

gala_bin = executable(
	'gala',
	gala_bin_sources,
	dependencies: [gala_dep, gala_base_dep],
	include_directories: config_inc_dir,
	install_rpath: mutter_typelib_dir,
	install: true,
)
