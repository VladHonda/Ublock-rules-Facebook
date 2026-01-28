! =====================================================
! FACEBOOK CLEANUP — STABLE VERSION (NO GRAY SCREEN)
! =====================================================

! -----------------------------
! SIDEBAR / SUGGESTIONS
! -----------------------------
facebook.com##div[data-pagelet^="PeopleYouMayKnow"]
facebook.com##div[data-pagelet*="PYMK"]
facebook.com##div:has(a[href*="/friends/suggestions"])
facebook.com##div[role="complementary"] div:has-text("People You May Know")
facebook.com##div[role="complementary"] div:has-text("Suggested for You")

! -----------------------------
! STORIES
! -----------------------------
facebook.com##div[data-pagelet^="Stories"]
facebook.com##div[role="region"]:has(a[href*="/stories/"])
facebook.com##div[role="complementary"] div:has(a[href*="/stories/"])

! -----------------------------
! REELS
! -----------------------------
facebook.com##div[role="navigation"] a[href*="/reels"]
facebook.com##div[role="feed"] div:has(a[href*="/reels/"])

! -----------------------------
! BUTTONS
! -----------------------------
facebook.com##a[aria-label="Join Group"]
facebook.com##div[aria-label="Join Group"]
facebook.com##a[aria-label="Follow"]
facebook.com##div[aria-label="Follow"]
facebook.com##a[aria-label="Reels"]
facebook.com##div[aria-label="Reels"]
