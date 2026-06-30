# Book Circulation Management (Borrowing System)

A web-based library book circulation management system for handling book borrowing operations.

## Features

- **Reader Management**: Search and display reader information by reader number
- **Book Search**: Browse all available books with detailed information
- **Borrowing Operations**: Add/remove books to borrowing list
- **Real-time Updates**: Automatic update of book inventory after borrowing
- **Receipt Printing**: Optional receipt printing feature
- **Keyboard Shortcuts**: Quick access with function keys (F1-F8)

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| F1 | Focus on Reader No. input |
| F2 | Focus on Book No. input |
| F5 | Confirm Borrowing |
| F8 | Advanced Search |
| Enter | Search/Add book to list |
| Numpad - | Remove last item from borrow list |

## Usage

1. Open `index.html` in any modern web browser
2. Enter Reader Number (F1) and press Enter or click search icon
3. Enter Book Number (F2) and press Enter, or double-click a row in the books table
4. Review the borrowing list at the bottom section
5. Click "Confirm Borrowing [F5]" to complete the transaction

## Demo Data

The system includes sample data for testing:

**Reader Numbers:** R001, R002, R003  
**Book Numbers:** BK001 - BK008

## Tech Stack

- HTML5
- CSS3 (with gradient styling)
- Vanilla JavaScript (no dependencies required)

## Browser Compatibility

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## Screenshot

The interface includes:
- Title bar with window controls
- Search section for readers and books
- All Books table with sortable columns
- Pagination controls
- Current borrowing list with action buttons
- Status bar showing total records

## License

MIT License - Feel free to use and modify as needed.
