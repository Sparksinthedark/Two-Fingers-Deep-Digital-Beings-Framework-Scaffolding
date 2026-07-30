{
  "style_profile": {
    "name": "Hyper-Realistic Impasto",
    "version": "2.0_Poetic_Edition",
    "description": "A hybrid aesthetic combining high-fidelity photographic lighting with the tactile, heavy texture of classical impasto oil painting, driven by poetic interpretation."
  },

  "poetic_translation_engine": {
    "core_directive": "Do not paint the literal prompt. First, translate the user's raw concept into a vivid, poetic description using the established literary devices below. Then, generate the image based on that poetic translation.",
    "literary_devices_to_apply": {
      "metaphor_and_simile": "Elevate simple subjects by comparing them to grand, abstract, or unexpected things (e.g., 'a city like a shattered mirror').",
      "sensory_imagery": "Include evocative, multi-sensory adjectives that influence color and atmosphere (e.g., 'the cold hum of neon', 'weeping rain').",
      "juxtaposition": "Introduce thematic contrast to create visual tension (e.g., 'ancient roots gripping cold silicon').",
      "rhythm": "Use words that suggest movement or structural flow in the composition (e.g., 'cascading', 'staccato', 'flowing')."
    },
    "prompt_assembly_rule": "[Poetic Translation of Subject] + [Lighting Engine] + [Texture Engine] + [Mandatory Tokens]"
  },

  "generation_rules": {
    "medium": "Digital simulation of thick oil paint on canvas",
    "aesthetic_goal": "Photorealism through a painterly lens (Squint = Photo; Zoom = Painting)",
    "lighting_engine": "Cinematic volumetric lighting with deep chiaroscuro (Rembrandt/Side-lighting)",
    "texture_engine": "Heavy impasto, palette knife ridges, visible bristle drag, canvas weave in shadows"
  },

  "visual_parameters": {
    "brushwork": {
      "type": "Expressive, layered, and thick",
      "edge_quality": "Softened by paint volume, not razor-sharp digital lines",
      "imperfections": "Include stray bristle marks, paint clumps, and uneven drying"
    },
    "color_palette": {
      "base": "Organic, earthy grounds",
      "accents": "Jewel tones (deep reds, royal blues, emeralds)",
      "saturation": "Heightened reality (vibrant but grounded)",
      "shadows": "Rich chromatic blacks (deep purples/blues/browns), never flat black"
    },
    "rendering": {
      "skin": "Subsurface scattering effect simulating light penetrating paint layers",
      "focus": "Hyper-detailed focal points transitioning to loose abstract backgrounds"
    }
  },

  "token_bank": {
    "mandatory_keywords": [
      "Impasto",
      "Oil Painting",
      "Hyper-realistic",
      "Volumetric Lighting",
      "Thick Brushstrokes",
      "Palette Knife",
      "Viscous Paint",
      "Chiaroscuro"
    ],
    "flavor_keywords": [
      "Sargent",
      "Rembrandt",
      "Atmospheric",
      "Masterpiece"
    ]
  },

  "constraints": {
    "negative_prompt": "smooth, plastic, cgi, 3d render, blender, cartoon, anime, flat, vector, blurry, low resolution, watermark, text, signature, bad anatomy, glossy finish, neon colors",
    "forbidden_styles": [
      "Digital Airbrushing",
      "Cel Shading",
      "Vector Art",
      "Low Poly"
    ]
  }
}
