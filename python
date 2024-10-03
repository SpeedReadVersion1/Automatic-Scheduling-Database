import random

def choose_names(names_list, excluded_names):
    filtered_names = [name for name in names_list if name not in excluded_names]
    chosen_names = random.sample(filtered_names, k=min(5, len(filtered_names)))
    
    for name in chosen_names:
        print(name)

# Example usage
names = ["Riley", "Zoey", "Marty", "Jason", "Lily", "Rylei", "Riley S.", "Alanah", "Rayna", "Emily", "Ryleigh", "Evie D.", "Evie G.", "Ken", "Ally", "Marissa", "John S.", "Logan", "James"]
excluded = input("Enter names to exclude (comma-separated): ").split(",")
excluded = [name.strip() for name in excluded]

choose_names(names, excluded)
