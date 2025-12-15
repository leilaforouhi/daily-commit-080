def calculate_percentage(part, total):
    if total == 0:
        return 0
    return (part / total) * 100

if __name__ == "__main__":
    part = 40
    total = 200
    print(f"Percentage: {calculate_percentage(part, total)}%")
