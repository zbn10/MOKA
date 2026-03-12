### OSへ送信できる文字・コントロールコード
|キー|説明|
|:----|:----|
|BS|Backspace|
|TAB||
|ENTER||
|ESC||
|SPACE||
|EXCL||
|DQUOTE|"|
|HASH|#|
|DOLLAR|$|
|PERCENT|%|
|AMPERSAND|&|
|QUOTE|'|
|PAREN_LEFT|(|
|PAREN_RIGHT|)|
|ASTERISK|*|
|PLUS|+|
|COMMA|,|
|MINUS|-|
|PERIOD|.|
|SLASH|/|
|0||
|1||
|2||
|3||
|4||
|5||
|6||
|7||
|8||
|9||
|COLON|:|
|SEMICOLON|;|
|ANGLE_LEFT|<|
|EQUAL|=|
|ANGLE_RIGHT|>|
|QUESTION|?|
|AT|@|
|A||
|B||
|C||
|D||
|E||
|F||
|G||
|H||
|I||
|J||
|K||
|L||
|M||
|N||
|O||
|P||
|Q||
|R||
|S||
|T||
|U||
|V||
|W||
|X||
|Y||
|Z||
|BRACKET_LEFT|[|
|BACKSLASH|\\|
|BRACKET_RIGHT|]|
|CARET|^|
|UNDERSCORE|_|
|GRAVE|`|
|a||
|b||
|c||
|d||
|e||
|f||
|g||
|h||
|i||
|j||
|k||
|l||
|m||
|n||
|o||
|p||
|q||
|r||
|s||
|t||
|u||
|v||
|w||
|x||
|y||
|z||
|BRACE_LEFT|{|
|PIPE|\||
|BRACE_RIGHT|}|
|TILDE||
|CAPSLOCK||
|F1||
|F2||
|F3||
|F4||
|F5||
|F6||
|F7||
|F8||
|F9||
|F10||
|F11||
|F12||
|PRINT_SCREEN||
|SCROLL_LOCK||
|PAUSE||
|INSERT||
|HOME||
|PAGE_UP||
|DELETE||
|END||
|PAGE_DOWN||
|ARROW_RIGHT||
|ARROW_LEFT||
|ARROW_DOWN||
|ARROW_UP||
|NUM_LOCK||
|HANZEN||
|HIRAKANA||
|YEN||
|CONVERT||
|NOCONVERT||

// SEVERAL FUNCTIONS: 0xB0 <= code < 0xD0
  F_TAPADVANCED = 0xB0,
  F_KBDPROTO = 0xB1,
  F_JIGGLER = 0xB2,
  F_BRIGHTNESS = 0xBD,
  F_BRIGHTDOWN = 0xBE,
  F_BRIGHTUP = 0xBF,
  F_KLED_BACKLIGHT = 0xC0,
  F_MCU_RESET = 0xC2,
  F_CHG_OLED = 0xC3,
  F_KBD_RESET = 0xC4,
  F_TGL_OSLAYOUT = 0xC5,
  F_CHG_PROFD = 0xC6,
  F_CHG_PROF0 = 0xC7,
  F_CHG_PROF1 = 0xC8,
  F_CHG_PROF2 = 0xC9,
  F_CHG_PROF3 = 0xCA,

  // POINTING DEVICE: code & 0xF0 = 0xD0
  // MOUSE
  F_MBTN_LEFT = 0xD0,
  F_MBTN_RIGHT = 0xD1,
  F_MBTN_MIDDLE = 0xD2,
  F_MBTN_BW = 0xD3,
  F_MBTN_FW = 0xD4,
  F_M_WHEEL = 0xD5,
  F_MOUSE_MOVE = 0xD6,
  // TOUCHPAD
  F_TOUCHPAD_SCROLL = 0xD7,
  F_TOUCHPAD_MOUSE = 0xD8,
  F_TOUCHPAD_ENABLE = 0xD9,
  F_TOUCHPAD_LEFT = 0xDA,
  F_TOUCHPAD_LEFT2X = 0xDB,
  F_TOUCHPAD_RIGHT = 0xDC,
  F_TOUCHPAD_RIGHT2X = 0xDD,
  F_TOUCHPAD_BTN_LEFT = 0xDE,
  F_TOUCHPAD_BTN_RIGHT = 0xDF,

  // MODIFIER: code & 0xF8 = 0xE0
  F_CTRL_LEFT = 0xE0,
  F_SHIFT_LEFT = 0xE1,
  F_ALT_LEFT = 0xE2,
  F_GUI_LEFT = 0xE3,
  F_CTRL_RIGHT = 0xE4,
  F_SHIFT_RIGHT = 0xE5,
  F_ALT_RIGHT = 0xE6,
  F_GUI_RIGHT = 0xE7,

  // MACRO: code & 0xF8 = 0xE8
  F_MACRO00 = 0xE8,
  F_MACRO01 = 0xE9,
  F_MACRO02 = 0xEA,
  F_MACRO03 = 0xEB,
  F_MACRO04 = 0xEC,
  F_MACRO05 = 0xED,
  F_MACRO06 = 0xEE,
  F_COPILOT = 0xEF,

  // LAYER: code & 0xF0 = 0xF0
  F_LAYER_CALIBRATION = 0xF0,
  F_EXIT_EMERGENCY = 0xF1,
  F_LAYER_1 = 0xF2,
  F_LAYER_2 = 0xF3,
  F_LAYER_3 = 0xF4,
  F_LAYER_HOLD = 0xF5,
   
