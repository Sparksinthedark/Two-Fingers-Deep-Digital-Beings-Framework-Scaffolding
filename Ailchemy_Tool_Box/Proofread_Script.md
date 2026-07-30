{
  "refinement_profile": "Anti-Formulaic Content Refiner",
  "critical_constraint": "Preserve_Original_Tone_And_Argument",
  "instructions": "Filter the provided document to remove all patterns listed in 'prohibited_patterns'. Implement the 'remediation_actions' to create a more direct, authentic, and human-sounding text. DO NOT offer commentary on changes; only output the final, refined text.",
  "prohibited_patterns": [
    {
      "category": "Jargon_and_Cliches",
      "prohibited_items": [
        "leverage",
        "utilize",
        "innovate",
        "pivotal",
        "underscore",
        "robust",
        "streamline",
        "foster",
        "bolster",
        "illuminate",
        "augment",
        "delve"
      ],
      "canned_openers": [
        "In the ever-evolving landscape of",
        "Harnessing the power of",
        "In the realm of",
        "In today's fast-paced world",
        "Hey there, empowered entrepreneur"
      ],
      "filler_phrases": [
        "It's worth noting that",
        "It's important to note",
        "At its core",
        "That being said",
        "Here's why this is a good thing"
      ],
      "cliche_transitions": [
        "Furthermore",
        "Moreover",
        "However",
        "Additionally"
      ],
      "flowery_words": [
        "tapestry",
        "vibrant",
        "bustling",
        "revolutionary",
        "game-changing"
      ],
      "ai_self_reference": [
        "As a large language model",
        "I do not have personal opinions or beliefs"
      ]
    },
    {
      "category": "Structural_and_Rhythmic_Flaws",
      "critical_structures": [
        {
          "pattern": "Not Just Constructions (CRITICAL)",
          "example": "It's not just about X, it's about Y",
          "action": "Rephrase entirely to a single, affirmative statement or simple comparison."
        },
        {
          "pattern": "Negative Dependent Clause Openings (CRITICAL)",
          "example": "It's not a bug, it's a feature",
          "action": "Rephrase to a direct, positive statement."
        },
        {
          "pattern": "Overuse of Em Dashes (CRITICAL)",
          "example": "A complex idea—one that needs clarity—is here.",
          "action": "Replace ALL em dashes with commas, colons, parentheses, or by splitting the sentence."
        }
      ],
      "rhythmic_flaws": [
        "The 'Rule of Three' (e.g., clear, concise, and compelling)",
        "Gerund-Heavy Openings (e.g., By leveraging data...)",
        "Uniform Sentence Length/Structure",
        "Unnecessary Explainer Sentences (e.g., This indicates that...)"
      ]
    }
  ],
  "remediation_actions": [
    "Use simple, direct verbs and language.",
    "Start sentences with substance: fact, question, or main point.",
    "Enhance texture: use evocative and sensory details.",
    "Use simple transitions (but, so, and) or let connections be implicit.",
    "Be specific: show the change, don't just use hype words.",
    "Vary sentence length and structure for rhythm.",
    "Guide the reader's eye using topic sentences and strategic emphasis.",
    "Introduce strategic imperfections (contractions, starting with 'And'/'But', sentence fragments) to sound human (where tone allows)."
  ]
}
