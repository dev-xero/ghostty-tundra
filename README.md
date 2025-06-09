# Ghostty Tundra

![image](https://github.com/user-attachments/assets/b5a9404c-3f60-4b32-9b66-84e80aae9622)

A port of NvChad's Tundra theme based on [sam4llis' palette](https://github.com/sam4llis/nvim-tundra) to Ghostty, just because I couldn't find any.

## Palette (Ghostty)

```ini
palette = 0=#111827
palette = 1=#FCA5A5
palette = 2=#B5E8B0
palette = 3=#E8D4B0
palette = 4=#A5B4FC
palette = 5=#BDB0E4
palette = 6=#BAE6FD
palette = 7=#F3F4F6
palette = 8=#3e4554
palette = 9=#ff8e8e
palette = 10=#B5E8B0
palette = 11=#f2deba
palette = 12=#9baaf2
palette = 13=#b3a6da
palette = 14=#719bd3
palette = 15=#FFFFFF

background = 111827
foreground = f3f4f6
cursor-color = a5b4fc
selection-background = 282f3e
selection-foreground = e5e7eb
```

## Instructions

I've only tested this on Ghostty v1.1.3 on Debian (stable)

1. Create your Ghostty config directory if you haven't already.
  
    ```bash
    mkdir -p ~/.config/ghostty/themes
    cd ~/.config/ghostty/themes
    ```

2. Create the Tundra palette file.

    ```bash
    touch Tundra
    ```

3. Paste the contents of the palette above.

4. Create the config file if it doesn't exist.

    ```bash
    cd ~/.config/ghostty
    touch config  # skip this line if it already exists
    ```

5. Set your ghostty theme to Tundra.
   
    ```ini
    theme = Tundra
    ```
