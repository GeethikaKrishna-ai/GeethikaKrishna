# Occupational Skin Disease App - Design Documentation

## Project Overview
**App Name:** Occupational Skin Disease  
**Platform:** Mobile (iOS/Android)  
**Primary Purpose:** Healthcare application for tracking and managing occupational skin conditions

## Design System

### Color Palette
- **Primary Gradient:** Pink to Purple (`#FF69B4` → `#9B59B6`)
- **Secondary:** Orange (`#FF8C00`)
- **Success:** Green (`#00C853`)
- **Background:** Light purple/pink gradient
- **Accent:** White for buttons and input fields

### Typography
- Clean, modern sans-serif font
- High contrast text on gradient backgrounds

---

## Screen Flow

### 1. Welcome Screen
**Elements:**
- Large triangular play icon/logo (black, layered design)
- "Hello" greeting text in bold script font
- "Get Started" button (white background, rounded)
- Full gradient background (pink to purple)
- Status bar showing 3:18, signal, WiFi, battery indicators

**Purpose:** Initial landing/splash screen to welcome users and begin onboarding

---

### 2. Sign In Screen
**Header:** ← Back  
**Title:** Sign-in  
**Subtitle:** HKM Healthcare

**Authentication Options:**
- "Sign Up With Phone" button (white, rounded)
- "Sign Up With Email" button (white, rounded)

**Social Media Login:**
- Facebook icon (blue)
- Google icon (multicolor)

**Design:** Pink to purple gradient background with centered layout

**User Actions:** Choose authentication method

---

### 3. Sign-up Email Screen
**Header:** ← Back  
**Title:** Sign up

**Subtitle:** Sign up with Email

**Form Fields:**
- **Username:** Input field with outlined border
- **Password:** Input field with show/hide eye icon

**Primary Button:**
- "Continue" button (white)

**Divider:** "Or" text

**Alternative Option:**
- "Sign In With Phone" button (white)

**Social Media Options:**
- Facebook icon (blue)
- Google icon (multicolor)

**Design:** Pink to purple gradient background

**Purpose:** Email registration flow

---

### 4. Personal Information Screen
**Title:** Personal Information

**Progress Indicator:** 5-step progress bar (currently on step 3)

**Form Fields:**
- **Name:** Input field with "Username" placeholder
- **D.O.B:** Date of birth input field
- **Age:** Input field
- **Gender:** Input field

**Navigation:**
- "Continue" button (white)

**Design:** Pink to purple gradient background with simple form layout

**Purpose:** Collect user demographic data

---

### 5. Your Role Screen
**Title:** Your Role

**Progress Indicator:** 4-step progress bar (currently on step 4)

**Section Title:** Types of construction work

**Dropdown Fields:**
Three identical dropdown menus labeled "Work" with dropdown arrows

**Section:** Experience Level

**Experience Options:**
- 0-1 Years
- 1-3 Years
- 3-6 Years
- 6-10 Years
- Above 10 Years

**Navigation:**
- "Back" button (white)
- "Continue" button (white)

**Design:** Pink to purple gradient background

---

### 6. Material Exposure Screen
**Header:** Material Exposure  
**Subheader:** Which Material Do You Work With Regularly?

**Progress Indicator:** 5-step progress bar (currently on step 5)

**Info Alert:**
"Select all materials you're regularly exposed to. This helps us provide personalized safety recommendations."

**Section:** Common Materials  
**Subtitle:** Select all that apply (3 selected)

**Material Options:**
- Cement ✓
- Solvents ✓
- Dust ✓
- Metals
- Paints
- Wood

**Navigation:**
- "Back" button (white)
- "Continue" button (white)

**Design Note:** Orange to purple gradient background with information icon

---

### 7. Symptoms and Duration Screen
**Title:** Symptoms & Duration

**Progress Indicator:** 4-step progress bar

**Instructions:**
"Select All Symptoms You're Currently Experiencing. This Help Us Prioritize Your Safety."

**Section:** Select All That Apply

**Symptom Options:**
- Redness Or Irritation
- Dry Or Flaky Skin
- Itching Or Burning
- Rash Or Bumps
- Discoloration Or Dark Spots
- Blisters Or Swelling
- No Concerns (Just Monitoring)

**Navigation:**
- "Back" button (white)
- "Continue" button (white)

**Design:** Pink to purple gradient background

---

### 8. Skin Scan Screen
**Title:** Skin Scan  
**Subtitle:** Take or upload photo of affected area

**Upload Area:**
Large pink rectangular area for image preview/upload

**Capture Section:**
📷 **Capture Image**
- Icon with upload symbol
- "Tap To Take Photo Or Upload"
- "JPG, Png Format Support"

**Photo Guidelines:**
1. Keep Camera Steady
2. Ensure Affected area is clearly visible
3. Ensure Proper Lighting

**Action Buttons:**
- "Upload" button (white)
- "Back" button (white)
- "Continue" button (white)

**Design:** Pink to purple gradient background with dotted border upload area

---

### 9. Home Dashboard Screen
**Header:** Hi Name!  
Stay safe

**Safety Score Card:**
- "Your safety score"
- Progress bar showing 100%

**Alert Card - UV Alert:**
- 🌞 Sun icon
- "UV alert!"
- "High UV Index today 8/10"
- "Apply SPF 30+ sunscreen every 2 hours"

**Daily Activity Card:**
- 📷 Camera icon
- "Daily skin check"
- "Earn 100 points: take 2 minutes"
- "Start Scan" button (white)

**Quick Action Buttons:**
- ⚡ Day streak
- 🎁 Free gifts
- 📊 Total score

**Risk Indicators:**
Two cards with 'O' symbol:
- "represent high risk"
- "represent high risk"

**Design:** Pink to purple gradient with white action cards

---

### 10. Analysis Screen
**Status:** Analysis Complete  
**Subtitle:** Your skin has been processed

**Success Card:**
- Green checkmark icon
- "+ 50 Points Earned"
- "Keep your safety streak for bonus point"

**Risk Alert Card (Yellow):**
- ⚠️ Warning icon
- "Medium Risk Detected"
- "Allergic Contact Dermatitis likely. Follow recommendation below."

**Analysis Results Section:**
- 🔍 Analysis icon with "Medium Risk" badge
- "Based on image and symptom analysis"

**Detected Condition:**
- "Allergic Contact Dermatitis"
- Confidence bar: 84% (red progress bar)

**⚠️ Immediate Action:**
- Wash affected area with mild soap and cool water
- Apply fragrance-free moisturizer or prescribed cream
- Avoid contact with cement and chemicals
- Consult healthcare provider if condition worsen

**Navigation:**
- "Back to Home" button (green)

**Design:** Light background with colored alert cards

---

### 11. Product Marketplace Screen
**Header:** 🎁 Rewards Store  
**Subtitle:** Redeem points for free products

**Search Bar:** 
- "Search products..." with search icon

**Special Offer Card (Purple/Magenta):**
- ⚡ Special Offer icon
- "Complete 3 morescan this week and get 100 bonus points!"
- Progress bar: 2/5

**Category Tabs:**
- All Items
- PPE
- Skincare

**Product Cards:**

1. **Premium Nitrile Gloves**
   - Image of yellow and black gloves
   - ⭐ 4.8 rating
   - "In Stock" badge
   - 💰 150pts
   - ➕ "Not Enough Points" badge

2. **Safety Goggles**
   - Image of blue safety goggles
   - "Anti-fog, UV Protection"
   - ⭐ 4.8 rating
   - "In Stock" badge
   - 💰 120pts
   - ➕ "Not Enough Points" badge

3. **SPF 50+ Sunscreen**
   - Image of orange sunscreen bottle
   - "Water-resistant broad spectrum"
   - ⭐ 4.8 rating
   - "In Stock" badge
   - 💰 100pts
   - ➕ "Not Enough Points" badge

**Design:** Light pink/white background with product cards

---

### 12. Claim Confirmation Screen
**Header:** ← Back  
**Title:** Confirm Your Claim  
**Subtitle:** Review and confirm delivery details

**Selected Product Card:**
- 🛒 Shopping cart icon
- "Selected Product"
- Image: Premium Nitrile Gloves
- Product name: "Premium Nitrile Gloves"
- Description: "Chemical-resistant, powder-free protective glove"
- ⭐ 4.8 rating | "Free Item" badge (green)
- Cost: 150 points | Balance: -100 pts

**Delivery Information Section:**
- 📍 Location icon
- "Delivery Information"
- Subtitle: "Where should we send your free product?"

**Form Fields:**
- **Full Name** (with user icon)
- **Phone Number** (with phone icon)
- **Email Address** (with email icon)
- PIN Code
- Address

**Action Button:**
- 🎁 "Confirm Claim (150 points)" button (purple)

**Design:** Purple gradient background with white form card

---

### 13. Claim Success Screen
**Status:** Claim Successful

**Visual Elements:**
- Large green checkmark icon (circular)
- Success message: "Your free safety product has been claimed and will be delivered soo"

**Product Card:**
- Image: Premium Nitrile Gloves (yellow and black)
- Product name: "Premium Nitrile Gloves"
- Order #125267

**Order Status Timeline:**

1. ✅ **Order Confirmed** (Green)
   - "Confirmation sent to your email"

2. ✅ **Processing** (Purple)
   - "Will ship within 24 hours"

3. 📧 **Tracking Info** (Blue)
   - "Email sent very soon"

**Points Summary:**
- **Points Used:** -150 pts
- **Remaining Balance:** 100 points (orange badge)

**Action Button:**
- "Back to Home" button (bright green)

**Design:** White background with clean order tracking cards

**Time:** 3:18
**Header Elements:** Menu icon (left), Logo icon (right)

---

## Key Features

### Authentication
- Multiple sign-up options (Phone/Email)
- Social media integration (Facebook, Google)

### User Onboarding
- Personal information collection
- Work experience assessment
- Material exposure tracking

### Health Tracking
- Symptom logging
- Duration tracking
- Photo-based skin analysis

### Dashboard
- Daily diary
- UV alerts
- Skin care routines
- Daily quests

### Analysis & Diagnosis
- AI-powered skin condition detection
- Priority-based alerts
- Detailed condition information

### E-commerce Integration
- Product recommendations
- Order placement
- Claim submission system

### Claim Management
- Easy claim submission
- Order tracking
- Delivery confirmation

---

## User Flow Summary

1. **Onboarding:** Welcome → Sign In/Sign Up → Personal Info → Role Selection → Material Exposure
2. **Assessment:** Symptoms & Duration → Skin Scan
3. **Main App:** Home Dashboard → Analysis
4. **Actions:** Product Marketplace → Claim Submission → Claim Success

---

## Design Notes

- Consistent gradient background creates brand identity
- White buttons provide clear CTAs against gradient
- Progress indicators show completion status
- Card-based layouts for information hierarchy
- Color-coded alerts (Yellow: Warning, Red: Critical, Green: Success)
- Mobile-first responsive design
- Accessible form inputs with clear labels

---

## Technical Considerations

- Image upload functionality for skin scans
- Form validation for user inputs
- Progress tracking across multi-step flows
- Integration with healthcare databases
- Secure authentication system
- E-commerce backend integration
- Push notification system for alerts

---

*Last Updated: December 2025*