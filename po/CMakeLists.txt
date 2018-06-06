include (Translations)
    add_translation_directory(${GETTEXT_PACKAGE})
    add_translation_catalog(${GETTEXT_PACKAGE}
    ../src/
)