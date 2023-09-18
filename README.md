# 🌐 Python Subnet Calculator
This calculator is designed to take an IP address as input, validate its correctness, determine its class (A, B, C, D, or E), and provide CIDR notation either given by the user or inferred from the IP class.

## 🌟 Features:
#### IP Validation:

🟢 Ensure the input IP is in the correct format (xxx.xxx.xxx.xxx).

🟢 Each segment (octet) should be between 0 and 255.

🟢 Identify the IP class (A, B, C, D, or E).

#### CIDR Notation:

🟢 User can input CIDR notation if known.

🟢 If CIDR is not provided, it is inferred based on the IP class.

#### Subnet Calculation: 
Depending on the IP class or CIDR.

🟢 Class A: 255.0.0.0

🟢 Class B: 255.255.0.0

🟢 Class C: 255.255.255.0

#### Subnet from CIDR:
🟢 Convert CIDR notation to subnet mask.

## 📝 Inputs:

**IP Address:** A valid IPv4 address.

**CIDR Notation (optional):** If not provided, the tool infers it from the IP class.

**Partitioning Preference:** Whether the user wants to partition based on the number of hosts or subnets.

**Number:** Depending on the above choice, the number of hosts or subnets.

## 📌 Outputs:

**Subnet Mask:** Displayed in decimal format.

**CIDR Notation:** Displayed as /xx (e.g. /24) format.

**Number of Hosts:** Total possible hosts in the subnet.

**Number of Subnets:** Total possible subnets.

**Network and Broadcast Addresses:** For the first two and the last two subnets.

## 🔧 Requirements:

### The user should input the IP in the correct format: 
Only 4 octets are separated by dots.

Each octet can contain numbers ranging from 0 to 255 only.

## 🚀 Usage Guide:
## Step 1: Download
Clone the repository:
```bash 
git clone https://github.com/kinanhino/subnet-calculator-python.git
```
## Step 2: Navigate to the directory:
```bash 
cd subnet-calculator-python
```

## Step 3: Give execute permissions to the script
```bash 
chmod +x python_subnet_calculator.py
```

## Step 4: Run the tool
```bash 
python python_subnet_calculator.py
```
Follow the prompts, provide the required inputs, and get your subnetting details.




